# Installation Guide

This document provides step-by-step instructions on setting up the environment and running the Python scripts for the Uber Data Analysis and Visualization project.

## Table of Contents
1. [Setting Up Google Cloud Platform (GCP)](#setting-up-google-cloud-platform)
2. [Environment Setup](#environment-setup)
4. [Data Orchestration](#data-orchestration)
5. [Data Analysis and Visualization](#data-analysis-and-visualization)

## Setting Up Google Cloud Platform (GCP) <a name="setting-up-google-cloud-platform"></a>

1. **Create a GCP Account:** If you don't have a GCP account, create one [here](https://console.cloud.google.com/).

2. **Create a Bucket:** Navigate to the GCP console and create a new bucket. Upload the transformed CSV file to this bucket.

3. **Create a VM Instance:** Go to the VM Instances page and click on "Create Instance". 

## Environment Setup <a name="environment-setup"></a>

1. sudo apt-get install update
2. sudo apt-get install python3-distutils
3. sudo apt-get install python3-apt
4. sudo apt-get install wget
5. wget https://bootstrap.pypa.io/get-pip.py
6. sudo python3 get-pip.py


## Setting Up Google Cloud Platform (GCP) <a name="setting-up-google-cloud-platform"></a>

1. **Create a GCP Account:** If you don't have a GCP account, create one [here](https://console.cloud.google.com/).

2. **Create a Bucket:** Navigate to the GCP console and create a new bucket. Upload the transformed CSV file to this bucket.

3. **Create a VM Instance:** Go to the VM Instances page and click on "Create Instance". 

## Data Orchestration <a name="data-orchestration"></a>

1. **Install Mage:** Within your VM, install Mage for data orchestration.

2. **Make a ETL:** Based on the files present in the mage folder, create the extraction, transformation and loading

3. **Run the Orchestration Script:** Navigate to the directory where the orchestration script is located and run it. 

This will consume the CSV file from the GCP bucket, transform the data and load using Python.

## Data Analysis and Visualization <a name="data-analysis-and-visualization"></a>

1. **Create Analysis Table:** In BigQuery, create the analysis table using the transformed data.

2. **Connect BigQuery to Looker:** Follow Looker's documentation to connect your BigQuery database to Looker.

3. **Create a Dashboard in Looker Studio:** Use the LookML files in the repository to create your dashboard in Looker Studio.

Congratulations, you've now set up your environment and run the scripts for the Uber Data Analysis and Visualization project! Please refer to the main README for additional information on the project structure and components.
