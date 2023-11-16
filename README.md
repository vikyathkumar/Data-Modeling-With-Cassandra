# Data-Modeling-With-Cassandra


# ETL Pipeline and Apache Cassandra Project

## Overview

This project involved building an ETL pipeline for preprocessing files and completing the Apache Cassandra coding portion. The goal was to work with a CSV file containing music app data and create tables for running specific queries.

## Part I: ETL Pipeline for Pre-Processing

- Developed an ETL pipeline in Python for efficient pre-processing of files.
- Executed the pipeline to handle data extraction, transformation, and loading tasks.
- Ensured clean and transformed data for further analysis.

## Part II: Apache Cassandra Coding

- Worked with the CSV file (`event_datafile_new.csv`) containing music app data.
- Created Apache Cassandra tables based on specific queries to model the database tables.
- Implemented queries to answer three key questions based on the provided data.

## Queries

1. **Query 1:**
   - Extracted the artist, song title, and song's length from the music app history.
   - Condition: sessionId = 338, itemInSession = 4.

2. **Query 2:**
   - Retrieved the name of the artist, song (sorted by itemInSession), and user (first and last name).
   - Condition: userid = 10, sessionid = 182.

3. **Query 3:**
   - Identified every user name (first and last) in the music app history who listened to the song 'All Hands Against His Own'.

## Project Outcome

- Successfully created denormalized data tables in Apache Cassandra for efficient querying.
- Demonstrated expertise in data modeling and database management using Apache Cassandra.
- Executed complex queries to extract valuable insights from the music app data.

## Technologies Used

- **Programming Language:** Python
- **Database:** Apache Cassandra
