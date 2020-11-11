## Udacity Data Streaming NanoDegree Project 2: San Francsico Crime Statistics

#### Project rubric can be found here: https://review.udacity.com/#!/rubrics/2676/view

## Purpose

#### This project draws data on San Fran crime incidents from Kaggle and outputs a structured stream to provide statistical analysis of the data. This analysis can be used by city officials to identify which areas are most afflicted by crimes to actions can be taken.

#### This analysis can be used to answer several questions such as:

* What are the top types of crimes in San Francisco?

* What is the crime density by location?

## Running the Project

* If using a <code>pip</code> environment, use <code>pip install -r requirements.txt</code> to install requirements

* Use the commands below to start the Zookeeper and Kafka servers:

    * <code>bin/zookeeper-server-start.sh config/zookeeper.properties
      bin/kafka-server-start.sh config/server.properties</code>

* Start the bootstrap server using the Python command <code>python producer_server.py</code>

