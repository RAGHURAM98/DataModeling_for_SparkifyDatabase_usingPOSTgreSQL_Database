### Sparkify

created a data model for sprakify database using start schema and build a ETL process to insert the data into 

### Data modeling for sparkify database:

start schema was used in creating table names.
<img src="Sparkify database.png" alt="Star Schema" style="height: 500px; width:500px;"/>

## Contents
1. sql_queries.py
    1. Contains all the sql queries (CREATE, INSERT, DROP) against the database used in etl.py
2. create_tables.py
    1. Drops and recreates tables.
3. etl.py
    1. reads and processes files from song_data and log_data and loads them into the tables.
4. data/log_data
    1. Contains all the file for log_data
5. data/song_data
    1. Contains all the files for song_data
6. test.ipynb
    1. Jupyter notebook file with test sql to test etl process in development.
7. README.md

## RUN instructions in Terminal in order
1. python sql_queries.py
2. python create_tables.py
3. python etl.py



