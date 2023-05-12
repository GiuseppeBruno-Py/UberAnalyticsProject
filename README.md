# Project Title: Uber Data Analysis and Visualization

This README outlines the process and tools used in this project that focuses on consuming a dataset of general Uber information and presenting it via a dashboard with multiple filters and indicators.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Modeling](#data-modeling)
3. [Data Transformation](#data-transformation)
4. [Data Orchestration](#data-orchestration)
5. [Data Analysis and Visualization](#data-analysis-and-visualization)
6. [Installation & Usage](#installation-and-usage)

## Introduction <a name="introduction"></a>

This project aims to effectively present an insightful view of the Uber dataset. The process involves data modeling, transformation, orchestration, and analysis that ultimately results in an interactive dashboard on Looker Studio. 

The primary dataset used in this project is `uber_data.csv`, which contains comprehensive information about Uber rides.

## Data Modeling <a name="data-modeling"></a>

The data modeling process was carried out using the `draw.io` tool. This step was crucial for identifying the fact and dimension tables and establishing relationships among them. This modeling's file is located in the root directory.

## Data Transformation <a name="data-transformation"></a>

The Python script `transform_data.py` was used to transform the original `uber_data.csv` dataset into structured fact and dimension tables based on the design conceived during the data modeling phase. This Python script uses the pandas library for data manipulation and transformation.

## Data Orchestration <a name="data-orchestration"></a>

For data orchestration, we employed the Mage tool within a Virtual Machine (VM) set up in Google Cloud Platform (GCP). The CSV file containing the transformed data was stored in a GCP bucket. The Mage folder contains the related files for this process.

## Data Analysis and Visualization <a name="data-analysis-and-visualization"></a>

The transformed data was loaded into Google BigQuery where the analysis table was created. This table was then used in Looker Studio to create an interactive dashboard for data analysis and visualization. There is a pdf file of this panel in the root directory.

Link: https://lookerstudio.google.com/reporting/dc53a504-90c6-4e39-a804-9dd62785ca57

![Uber_Dashboard (3)-1](https://github.com/GiuseppeBruno-Py/UberAnalyticsProject/assets/91219935/f47b9e6a-91b3-49e9-ae5c-f9cc0121d0bc)


## Installation and Usage <a name="installation-and-usage"></a>

Detailed instructions for setting up the environment, running the Python scripts, and steps to use the Looker dashboard can be found in the `Installation.md` file in the repository.



