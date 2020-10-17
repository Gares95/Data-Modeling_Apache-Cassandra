# Data Modeling with Apache Cassandra
***
This repository simulates the creation of an Apache Cassandra database for a music streaming startup whose data currently resides in a directory of CSV files and are looking for an easy way to query the data and to analyze it. 

This project will include the files to create and define tables for a Apache Cassandra database and will serve as an example on how to make a connection to a Cassandra instance in your local machine and create a cluster to model data creating tables in order to be able to run queries of the data and process it and analyze it. 

# Data Files
***
### Event_data
The data that we are going to use is store in <em>event_data</em> directory which contains csv files with the next structure:

![alt text](https://raw.githubusercontent.com/Gares95/Data-Modeling_Apache-Cassandra/master/images/image_event_datafile_new.jpg)

The directory in this repository will only contain an example file.

# Python files
***
## Project_1B_Project_GuillermoGarcia.ipynb

This Jupyter notebook contains the steps to read the CSV files and create the cluster using Apache Cassandra to process the data and create tables in which we will load this data and we will visualize it using some queries. The notebook includes descriptive commentary and explanatory text indicating the different queries and statements and it also includes the lines of code to finally drop the tables and close the session and cluster connection.


### Credits
***
Udacity provided the template and the guidelines to start this project.
The completion of this was made by Guillermo Garcia and the review of the program and the verification that the project followed the proper procedures was also made by my mentor from udacity.
