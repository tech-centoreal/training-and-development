- [Foundation of Data Science](#foundation-of-data-science)
  - [Introduction to Data Science](#introduction-to-data-science)
    - [What is Data Science?](#what-is-data-science)
    - [Applications of Data Science in various sectors](#applications-of-data-science-in-various-sectors)
    - [Components of Data Science](#components-of-data-science)
    - [Python Libraries for Data Science](#python-libraries-for-data-science)
  - [Mathematical Preliminaries](#mathematical-preliminaries)
    - [Basic Probability Theory](#basic-probability-theory)
    - [Basic Statistics](#basic-statistics)
    - [Bayesian statistics](#bayesian-statistics)
    - [Probability distributions](#probability-distributions)
    - [Normal distribution](#normal-distribution)
    - [Poisson distribution](#poisson-distribution)
    - [Exponential distribution](#exponential-distribution)
    - [Mean, Median and Mode](#mean-median-and-mode)
    - [Central Limit theorem](#central-limit-theorem)
  - [Handling Data with Python](#handling-data-with-python)
    - [Importing Data sets into Python](#importing-data-sets-into-python)
    - [DataFrame object in Pandas](#dataframe-object-in-pandas)
    - [DataFrame operations](#dataframe-operations)
    - [Grouping Data](#grouping-data)
    - [Aggregating Data](#aggregating-data)
  - [Data Cleaning](#data-cleaning)
    - [Data types](#data-types)
    - [Handling Missing Values](#handling-missing-values)
    - [Handling Duplicates](#handling-duplicates)
    - [Handling Inconsistent Data](#handling-inconsistent-data)
    - [Handling Outliers](#handling-outliers)
  - [Data Visualization Fundamentals](#data-visualization-fundamentals)
    - [Principals of information visualization](#principals-of-information-visualization)
    - [Charting fundamentals](#charting-fundamentals)
    - [Applied Visualizations](#applied-visualizations)
  - [Matplotlib, Seaborn](#matplotlib-seaborn)
    - [2D Plots and Subplots](#2d-plots-and-subplots)
    - [3D Plots](#3d-plots)
    - [Animations and Interactivity](#animations-and-interactivity)
    - [Styling](#styling)
    - [Complex layouts with Pandas and Seaborn](#complex-layouts-with-pandas-and-seaborn)
  - [Data Munging and Exploratory Data Analytics](#data-munging-and-exploratory-data-analytics)
    - [Data Formatting and Normalization](#data-formatting-and-normalization)
    - [Feature Scaling](#feature-scaling)
    - [Dimentionality Reduction](#dimentionality-reduction)
    - [Summarizing Data Frames](#summarizing-data-frames)
    - [Descriptive Statistics](#descriptive-statistics)
    - [Correlation](#correlation)
    - [Scores and Rankings](#scores-and-rankings)
- [Advanced Data Science](#advanced-data-science)
  - [Statical Analysis](#statical-analysis)
    - [Inferential Statistics](#inferential-statistics)
    - [Statistical significance](#statistical-significance)
    - [Z-test](#z-test)
    - [T-test](#t-test)
    - [ANOVA](#anova)
    - [F Test](#f-test)
    - [Chi Square Test](#chi-square-test)
    - [Multivariate Analysis](#multivariate-analysis)
    - [Hypothesis Testing](#hypothesis-testing)
  - [Building and Validating Models](#building-and-validating-models)
    - [Linear regression](#linear-regression)
    - [Logistic regression](#logistic-regression)
    - [Nearest neighbour methods](#nearest-neighbour-methods)
    - [Clustering methods](#clustering-methods)
  - [Design of Experiments and Surveys - I](#design-of-experiments-and-surveys---i)
    - [Data science in the ideal vs real world](#data-science-in-the-ideal-vs-real-world)
    - [Components of Experimental Design](#components-of-experimental-design)
    - [Casuality](#casuality)
    - [Confounding](#confounding)
    - [Sampling bias and random sampling](#sampling-bias-and-random-sampling)
    - [Blocking and adjustment](#blocking-and-adjustment)
    - [Multiplicity](#multiplicity)
    - [Effect size,significance, & modelling](#effect-sizesignificance--modelling)
  - [Design of Experiments and Surveys - II](#design-of-experiments-and-surveys---ii)
    - [Comparision with benchmark effects](#comparision-with-benchmark-effects)
    - [Negative controls](#negative-controls)
    - [Non-significance](#non-significance)
    - [Design Process & Guidelines](#design-process--guidelines)
    - [One Factor Experiments](#one-factor-experiments)
    - [Multi-factor Experiments](#multi-factor-experiments)
    - [Taguchi Methods](#taguchi-methods)
    - [Report writing](#report-writing)
- [Data Science at Scale](#data-science-at-scale)
  - [Fundamentals of Data Engineering](#fundamentals-of-data-engineering)
    - [What is Data Engineering?](#what-is-data-engineering)
    - [Data Engineering Problems](#data-engineering-problems)
    - [Tools of a Data Engineer](#tools-of-a-data-engineer)
    - [Cloud Providers and Cloud Computing](#cloud-providers-and-cloud-computing)
  - [Data Engineering Tools](#data-engineering-tools)
    - [Fundamentals of databases](#fundamentals-of-databases)
    - [Parallel computing frameworks](#parallel-computing-frameworks)
    - [Spark, Hadoop and Hive](#spark-hadoop-and-hive)
    - [Workflow scheduling frameworks](#workflow-scheduling-frameworks)
    - [Airflow DAGs](#airflow-dags)
  - [Building Data Engineering Pipelines in Python](#building-data-engineering-pipelines-in-python)
    - [Scalable computing with Python](#scalable-computing-with-python)
    - [Cloud Environments](#cloud-environments)
    - [Coding Environments](#coding-environments)
    - [Data ingestion with Pandas](#data-ingestion-with-pandas)
    - [Data pipelines](#data-pipelines)
    - [ETL process](#etl-process)
  - [Data Modelling Tools](#data-modelling-tools)
    - [Data Modelling with PostgreSQL](#data-modelling-with-postgresql)
    - [Data Modelling with Apache Cassandra](#data-modelling-with-apache-cassandra)
    - [Storing data in cloud warehouses](#storing-data-in-cloud-warehouses)
    - [Building Data Lakes](#building-data-lakes)
  - [Prototyping Data Models](#prototyping-data-models)
    - [Linear Regression](#linear-regression-1)
    - [Logistic Regression](#logistic-regression-1)
    - [Keras Regression](#keras-regression)
    - [Automated Feature Engineering](#automated-feature-engineering)
  - [Data Models as Web Endpoints](#data-models-as-web-endpoints)
    - [Web service](#web-service)
    - [Echo service](#echo-service)
    - [Model persistence](#model-persistence)
    - [Model Endpoints](#model-endpoints)
    - [Deploying Endpoints with Gunicorn and Heroku](#deploying-endpoints-with-gunicorn-and-heroku)
  - [Pyspark for Batch pipelines](#pyspark-for-batch-pipelines)
    - [Introduction to Pyspark](#introduction-to-pyspark)
    - [Resilient distributed data sets](#resilient-distributed-data-sets)
    - [Structured data processing with SparkSQL and Python](#structured-data-processing-with-sparksql-and-python)
    - [Machine learning wtih Pyspark](#machine-learning-wtih-pyspark)
  - [Cloud Computing](#cloud-computing)
    - [Fundamentals of Google Cloud platform for Machine Learning](#fundamentals-of-google-cloud-platform-for-machine-learning)
    - [Cloud data warehouses with Google cloud platform](#cloud-data-warehouses-with-google-cloud-platform)
    - [Batch model pipeline in cloud](#batch-model-pipeline-in-cloud)
    - [Introduction to streaming model workflows](#introduction-to-streaming-model-workflows)
    - [Overview of Apache Kafka](#overview-of-apache-kafka)
    - [Sklearn Streaming](#sklearn-streaming)
    - [Streaming analytics systems](#streaming-analytics-systems)

# Foundation of Data Science

## Introduction to Data Science

### What is Data Science?

### Applications of Data Science in various sectors

### Components of Data Science

### Python Libraries for Data Science

## Mathematical Preliminaries

### Basic Probability Theory

### Basic Statistics

### Bayesian statistics

### Probability distributions

### Normal distribution

### Poisson distribution

### Exponential distribution

### Mean, Median and Mode

### Central Limit theorem

## Handling Data with Python

### Importing Data sets into Python

### DataFrame object in Pandas

### DataFrame operations

### Grouping Data

### Aggregating Data

## Data Cleaning

### Data types

### Handling Missing Values

### Handling Duplicates

### Handling Inconsistent Data

### Handling Outliers

## Data Visualization Fundamentals

### Principals of information visualization

### Charting fundamentals

### Applied Visualizations

## Matplotlib, Seaborn

### 2D Plots and Subplots

### 3D Plots

### Animations and Interactivity

### Styling

### Complex layouts with Pandas and Seaborn

## Data Munging and Exploratory Data Analytics

### Data Formatting and Normalization

### Feature Scaling

### Dimentionality Reduction

### Summarizing Data Frames

### Descriptive Statistics

### Correlation

### Scores and Rankings

# Advanced Data Science

## Statical Analysis

### Inferential Statistics

### Statistical significance

### Z-test

### T-test

### ANOVA

### F Test

### Chi Square Test

### Multivariate Analysis

### Hypothesis Testing

## Building and Validating Models

### Linear regression

### Logistic regression

### Nearest neighbour methods

### Clustering methods

## Design of Experiments and Surveys - I

### Data science in the ideal vs real world

### Components of Experimental Design

### Casuality

### Confounding

### Sampling bias and random sampling

### Blocking and adjustment

### Multiplicity

### Effect size,significance, & modelling

## Design of Experiments and Surveys - II

### Comparision with benchmark effects

### Negative controls

### Non-significance

### Design Process & Guidelines

### One Factor Experiments

### Multi-factor Experiments

### Taguchi Methods

### Report writing

# Data Science at Scale

## Fundamentals of Data Engineering

### What is Data Engineering?

### Data Engineering Problems

### Tools of a Data Engineer

### Cloud Providers and Cloud Computing

## Data Engineering Tools

### Fundamentals of databases

### Parallel computing frameworks

### Spark, Hadoop and Hive

### Workflow scheduling frameworks

### Airflow DAGs

## Building Data Engineering Pipelines in Python

### Scalable computing with Python

### Cloud Environments

### Coding Environments

### Data ingestion with Pandas

### Data pipelines

### ETL process

## Data Modelling Tools

### Data Modelling with PostgreSQL

### Data Modelling with Apache Cassandra

### Storing data in cloud warehouses

### Building Data Lakes

## Prototyping Data Models

### Linear Regression

### Logistic Regression

### Keras Regression

### Automated Feature Engineering

## Data Models as Web Endpoints

### Web service

### Echo service

### Model persistence

### Model Endpoints

### Deploying Endpoints with Gunicorn and Heroku

## Pyspark for Batch pipelines

### Introduction to Pyspark

### Resilient distributed data sets

### Structured data processing with SparkSQL and Python

### Machine learning wtih Pyspark

## Cloud Computing

### Fundamentals of Google Cloud platform for Machine Learning

### Cloud data warehouses with Google cloud platform

### Batch model pipeline in cloud

### Introduction to streaming model workflows

### Overview of Apache Kafka

### Sklearn Streaming

### Streaming analytics systems
