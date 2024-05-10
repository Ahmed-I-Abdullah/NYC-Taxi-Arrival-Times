# Apache Spark NYC Taxi Travel Time Prediction

This repository contains the code for predicting the travel time of taxis in New York City. The project uses the BigQuery public datasets on the Google Cloud Platform, specifically the trip records of NYC yellow cabs from the year 2016.

The prediction model is developed using Spark and Spark ML, with the main objective to analyze and build a Machine Learning model that leverages big data frameworks.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
The project uses the following python libraries, which need to be installed for the code to run successfully:
- gdown
- OS
- pyspark


## Data Import
The data for the project was downloaded from Google Drive using the gdown python library. The OS python library was then used to import the data into the operating system for easy retrieval.

The data content was read into a Resilient Distributed Dataset (RDD) object using the Spark textfile() function. This allows for parallel operations on data collections, efficient data sharing among cluster nodes, and provides a variety of transformation and action operations.

## Running the Code
After installing the prerequisites, you can run the notebook to build the prediction model. The notebook includes sections for data inspection, validation, model diagnostics and optimization.