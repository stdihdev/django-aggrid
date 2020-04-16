
**system requirements:**

-Python 3

-Django 2.0

-Mysql 5.3

-DjangoRestFramework

**Features Present:**

-Created a database in Mysql in local and uploaded the Employees details dataset

-Created RESTful API for the model which will be used to power the Plotly Charts 

-Created Charts in Plotly using JavaScript and using the RestAPI to power the charts

-Cache is implemented using the Djanco cache mechanism and the database is optimised using indexing method.

-Created Aggrid in Javascript and added filters and sorting features to the dataset columns

-Used the REST api to power the Dataset

**Steps to run the web application:**


-In the folder root , create the virtual environment


-Activate the virtual environment and install the requirements.txt file , run the migrations 


-Run the application using python manage.py runserver

**pointers**:

Please use the local Sqlite database to store the data , since the API is not globally exposed. ( I do not have an AWS account )

Import the dataset csv file into Mysql using the Mysql Workbench 

**API should be deployed using Zappa + AWS lambda**
