# Big Data Analytics with Spark: IMDB Dataset

## Project Overview
This project focuses on leveraging **Apache Spark (PySpark)** to process, clean, and analyze a large IMDB dataset. [cite_start]The goal is to extract meaningful insights regarding movie and television trends, genre diversity, and actor collaboration networks using distributed computing principles. 

## Key Features & Tasks
- [cite_start]**Data Cleaning:** Handling missing values and transforming raw strings (votes, duration, years) into structured numeric types. 
- [cite_start]**Trend Analysis:** Comparing popularity and ratings between movies and TV shows over time. 
- [cite_start]**Genre Insights:** Using Spark Window functions to rank top-performing movies within specific genres. 
- [cite_start]**Advanced Analytics:** Analyzing actor collaboration networks and identifying the most prolific creators in the industry. 

## Technologies Used
- [cite_start]**Language:** Python 
- [cite_start]**Framework:** Apache Spark (PySpark) [cite: 2, 5]
- [cite_start]**Platform:** Google Colab 
- [cite_start]**Concepts:** Lazy Evaluation, DAG, Caching, Window Functions, and Shuffle Optimization. 

## How to Run
1. [cite_start]Open the `BigDataHW2.ipynb` notebook in Google Colab. 
2. [cite_start]Upload the `IMBD.csv` dataset to your Colab session. 
3. [cite_start]Run the setup cell to install dependencies: `!pip install pyspark`. 
4. [cite_start]Execute the cells sequentially to build the Spark DAG and view the results. 

## Key Insights
- [cite_start]**Streaming Growth:** There is a significant increase in releases after 2010, reflecting the boom of streaming platforms. 
- [cite_start]**Content Quality:** TV shows consistently maintain higher average ratings than movies, suggesting stronger long-term audience engagement. 

## Contributors
- [cite_start]**Yousef Shihade** [cite: 2, 4]
- [cite_start]**Shada Esawi** [cite: 2, 4]
