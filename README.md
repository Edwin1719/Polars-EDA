# Polars-EDA

![Logo](https://media.licdn.com/dms/image/D5622AQHdVbfs8-qHHg/feedshare-shrink_800/0/1695092613884?e=2147483647&v=beta&t=hHe0_sTi6ahfQztoOSiDiV_10hfOwnz8u5ZdimwDho8)

## ETL and EDA using Polars, a high-performance DataFrame library optimized for speed and memory efficiency. The project leverages Polars' capabilities for fast data filtering, transformation, and aggregation, providing insights into ticket data with advanced visualization and analysis techniques.

## Features

-**Library Setup and Data Import:** Install required libraries and load datasets from CSV and Excel files into Polars DataFrames, preparing the data for analysis.

-**Data Cleaning and Transformation:** Filter relevant ticket entries, rename and restructure columns, cast data types, and split location fields to ensure consistency and usability.

-**Data Deduplication and Structuring:** Sort and remove duplicates from the dataset, and further organize the data by consolidating location and ticket attributes for clearer analysis.

-**Data Consolidation:** Join the ticket dataset with service data to create a unified dataset, enabling comprehensive analysis of ticket attributes and service metrics.

-**Exploratory Data Analysis (EDA):** Perform descriptive statistics, visualizations (bar charts, line graphs), and generate a word cloud to uncover patterns and trends in ticket types, providers, and ticket closure rates.

-**Data Export:** Save the final consolidated dataset as an Excel file for documentation and future analysis.

## Technologies used

-**Polars:** Polars is a high-performance DataFrame library optimized for fast data manipulation and analysis. It excels in ETL processes and exploratory data analysis by providing efficient functions for data cleaning, transformation, and aggregation, making it suitable for large datasets.

-**Pandas:** Pandas is a widely-used data manipulation library in Python, offering powerful tools for reading, writing, and cleaning data. It complements Polars by providing additional functionalities, enhancing the overall flexibility in data handling and exploration.

-**Matplotlib:** Matplotlib is a versatile plotting library that enables the creation of a wide range of static and interactive visualizations. It is used in this project to generate graphical representations of ticket data, helping to illustrate trends and insights effectively.

-**Seaborn:** Seaborn is a statistical visualization library built on Matplotlib that simplifies the creation of attractive and informative plots. It enhances data analysis by providing high-level interfaces for visualizing complex datasets, aiding in the interpretation of ticket data relationships.

-**WordCloud:** WordCloud is a library for generating word clouds from text data, visually representing word frequency. In this project, it is used to highlight the most frequently occurring providers in the dataset, providing insights into the service landscape.


## **Documentation**
! https://medium.com/@arias.juan.jose/etl-con-polars-en-python-975d17e9bcc4

! https://docs.pola.rs/

! https://www.youtube.com/watch?v=1PWqiHm9j5Y
