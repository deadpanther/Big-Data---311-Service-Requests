# CS-GY 6513 Big-Data Project---311-Service-Requests
## Project Member (Group 17)

Team Members:-
| Name          |    Net-Id     |
| ------------- | ------------- |
| Ritik Lnu     |       rl4017  |
| Neel Shah     |       nks8839 |
| Vishal Shah   |       vs2530  |

## Project Description
Inconsistent, incorrect, and missing data is quite common in today’s world which is often unavoidable. It may be due to human errors, inconsistent data management systems, or some other factors. In such cases, good data profiling and data cleaning techniques are quite important and inevitable to obtain data that can be used for further processing. We use data profiling to analyze the structure of our dataset and check if it has a standard structure for further processing. After evaluating the structure of our dataset we employ 
several techniques to clean the data. Some techniques are used to remove the outliers and other techniques are used to remove the missing values.
We use some open-source libraries to perform data profiling and data cleansing. We also use some custom User Defined Functions (UDFs) to perform data cleaning which we found
to be more effective than the open-source libraries. We use the 311 Service Requests dataset which encompasses
all non-emergency requests from the city, including but not limited to noise complaints, air quality issues and reports of
unsanitary conditions, etc. The 311 calls in New York City are publicly available on NYC OpenData.

## Approach

1. Profiling Data

The first step is to profile the data and know about the structure of the data and get an understanding of the colunms.

2. Cleaning the data

We will clean the dataset using openclean library and also with other custom user defined functions.

4. Analysis and visualise results

Finally we would analysis results of our data clean job and visualise our data before and after cleaning, by both our orignal strategies and our refined strategies.

5. Find Overlapping datasets

We analyse our dataset and measure the similarity on columns with our the dataset "311 Service requests", finding potential datasets with overlapping columns.

## Tools And packages

Below were the python packages used by us, they should be installed to reproduce the experiment:

1. openclean https://pypi.org/project/openclean/
2. pyspark https://pypi.org/project/pyspark/
3. Pandas https://pypi.org/project/pandas/

## Deliverables
1. The Project Report

An extensive analysis report of the whole process which has been performed on the dataset.

2. The Project Presentation

A presentation which has to be presented to the instructor to provide a quick summary of the process.

This is the repository for Big Data final project performed on 311 Service Requests Data from NYC Open Data
The data can be found at:
https://drive.google.com/drive/folders/1WK24hRhsgJLMvAYUpUHdP-uu8zSrBiwz?usp=sharing

## Data
The dataset can be found here: https://drive.google.com/drive/u/0/folders/15df1iAJCufYV2RJCDFuAHtNu31jj0v3G
The dataset can also be found with the unique identifier on HPC Peel Cluster: /user/CS-GY-6513/project_data/data-cityofnewyork-us.erm2-nwe9.csv

Thank You
