# Data-Modeling-Postgres
Udacity Project 1 of 6

## Sparkify Postgres Database
Create a Postgres database with tables designed to optimize queries on song play analysis for Sparkify, a fictional music streaming company.


## Schema design and ETL pipeline:

![final_ERD_Sparkify](https://user-images.githubusercontent.com/76083769/148631727-fddcd54d-08b4-4738-9ef8-c26925d596b0.jpg)

Star Schema with 1 Fact table (songplays) and 4 Dimension tables (users, songs, artists, and time).

erd_sparkify.JPG contains the ERD (star schema)
sql_queries.py contain DROP, CREATE, INSERT, and SELECT queries.
create_tables.py - create the database and tables using functions: create_database, drop_tables, create_table
etl.py - Extract, transform, load processes using functions: process_song_file, process_log_file, process_data


## Project Requirements
    Python 3
    pandas
    psycopg2
    A PosgreSQL database is available on localhost

## Running the Python Scripts
# At the terminal:
    python create_tables.py
    python etl.py

# In IPython:
    run create_tables.py
    run etl.py


    
