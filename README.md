# Spotify End-To-End Data Engineering Project

### Introduction
In this project, we will build an ETL(Extract, Transform, Load) pipeline using the Spotify API on AWS. The pipeline will retrieve data from the Spotify API, transform it to a desired format, and load in into a AWS data store.

## Architecture
![Architecture Diagram](https://github.com/mythili2734/Spotify-End-To-End-Data-Engineering-Project/assets/158598007/54c09f5a-9271-428b-9dc0-3b3422899d11)

### About Dataset/API
This API contains information about music artist, albums and songs - [spotify API](https://developer.spotify.com/documentation/web-api)

### Services used
 The Project utilizes the following AWS Services
  1. AWS S3 (Simple Storage Service)
  2. AWS Lambda
  3. Cloud Watch
  4. AWS Glue
  5. Amazon Athena
  6. Data Catalog

### Install Packages

 1. pip install pandas
 2. pip install numpy
 3.  pip install spotipy

 ### Project Execution Flow
 Extract Data from API -> Lambda Trigger (every 1 hour) -> Run Extract Code -> Store Raw Data -> Trigger Transform Function ->Transform Data and Load It -> Query Using Athena 



