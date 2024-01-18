# Bike Sharing Analysis Case Study: Building a Multiple Linear Regression Model

## Contents Overview
* [Overview](#overview)
* [Data Source](#data-source)
* [Technology Stack](#technology-stack)
* [Key Findings](#key-findings)

## Overview
- This case study delves into a dataset encompassing information about bike rentals for registered and casual users across various seasons and weather conditions, spanning the years 2018 and 2019.
- The objective is to construct a multiple linear regression model that predicts user demand. This model aims to assist management in comprehending the fluctuations in demand based on different variables. This understanding is crucial for tailoring business strategies to align with demand and to exceed customer expectations. Moreover, the model serves as a valuable tool for management to grasp the dynamics of demand in new markets.

## Data Source
> The data for this study has been furnished by the Upgrad team.
 - day.csv: This file includes detailed data on bike rentals for registered and casual users under varying seasonal and weather conditions during 2018 and 2019.
 - Readme.txt: A data dictionary that explains all column definitions and their corresponding values as referenced in the day.csv file.

## Technology Stack
- Python (version 3.0)
- Jupyter Notebook for analysis and modeling
- CSV and Excel for data handling

## Key Findings
- The final model indicates three significant factors that greatly influence the demand for shared bikes:
	- “temp” (exhibits a positive correlation)
	- “yr” (shows a positive correlation)
	- “Light Snow” condition

## Software Requirements
For this case study, Python 3.10 is utilized, and compatibility with versions above 3.6 is ensured. The Anaconda distribution is recommended for Python installation as it bundles all necessary libraries and Jupyter Notebooks. Expected libraries include:

+ NumPy
+ Pandas
+ Matplotlib
+ Seaborn
+ Math
+ Conda
+ Git
+ Jupyter Notebook
+ Statsmodels
+ Scikit-learn

**Important Note:**
An `environment.yaml` file is provided to facilitate the installation of all required libraries, ensuring a consistent workflow replication.