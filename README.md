# Data Engineering Project 1B
## Introduction

This is a project that I completed as part of the Udacity Data Engineering course. The scenario is that I am a data engineering working for a music streaming company. There are 3 basic requests that have to be completed as part of the project. They are as follows:
1.  Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

Note: the first two queries were straightforward, however the last query required a primary key and a clustering key in order to create unique identifiers. One thing that really hung me up was that you can not ever have more than one set of values for one primary key and that you will only see the last write. That was something was very important and had I understood that better, I would have saved me some frustration with the last query.

## Data and Code

The dataset for the project is contained in event_data directory, which is a directory of CSV files partitioned by date.

In addition to the data files, the project workspace includes two files:

* Project_1B_ Project_Template.ipynb : contains all the project data modelling code and ETL
* event_datafile_new.csv which is a smaller datast of the csv files. 


## Prequisites
* cassandra
* pandas
* csv
* os
* numpy
* json 
* Jupyter notebook and python 3 are needed to run the notebooks and python scripts.



## Installation
Download the required data sets and if required modify the directory paths. You also need access to a working Apache Cassandra installation. Follow the instructions on the jupyter notebooks to execute the ETL pipeline.

## License
[MIT](https://choosealicense.com/licenses/mit/)
