# Sparkify Capstone Project
Sparkify Capstone Project. In this project, we utilize the power of Apache Spark, a distributed data processing framework, to address a critical business problem: predicting customer churn. The project leverages PySpark, a Python library for Spark, to analyze large volumes of user data and make predictions about customer behavior.

## Project Overview
*Customer churn* is a common challenge faced by subscription-based businesses, such as streaming services like Sparkify. It refers to the phenomenon where customers stop using a service or cancel their subscriptions. Identifying and understanding churn is crucial for businesses because retaining existing customers is often more cost-effective than acquiring new ones.

The Sparkify Capstone Project is designed to help Sparkify, a fictional music streaming service, reduce customer churn. By analyzing user activity data, we aim to build predictive models that can identify customers at risk of churning. These models will help Sparkify take proactive measures to retain valuable customers by offering targeted promotions, personalized recommendations, or other incentives.


## Key Objectives
The primary objectives of the Sparkify Capstone Project include:

Data Exploration and Preprocessing: We start by exploring and preprocessing the dataset. This involves cleaning the data, handling missing values, and transforming it into a format suitable for analysis.

Feature Engineering: To build effective predictive models, we engineer relevant features from the user activity data. These features capture patterns and behaviors that may indicate customer churn.

Model Development: Using PySpark, we develop machine learning models capable of predicting customer churn. We experiment with different algorithms and techniques to find the best-performing model.

Model Evaluation: We assess the performance of our models using appropriate evaluation metrics, such as accuracy, precision, recall, and F1-score. This step ensures that our predictions are reliable.

Business Insights: We provide actionable insights based on the model's findings. Sparkify can use these insights to implement retention strategies and reduce customer churn.

## Installation and Dependencies
To run the Sparkify Capstone Project and utilize the code effectively, you'll need to set up an appropriate Python environment. We recommend using the Anaconda distribution of Python, which simplifies the management of packages and environments.

- the code was developed using `Python 3`. 
- `pyspark`: The PySpark library for working with Apache Spark, used here for data processing pipelines and ML training.
- `pandas`: A popular data manipulation and analysis library, used here for visualization purposes only.
- `seaborn and matplotlib`: Libraries for data visualization.
- `scikit-learn`: A powerful library for machine learning and model development, used to evaluate spark models easily.

## File Descriptions
- `Sparkify.ipynb`: Exploratory data analysis, data preprocessing, and the initial development of a pilot machine learning model.
- `LR`: Logestic regression model after training.
- `RF`:  Random Forest model after training.
- `GBT`: Gradient Boosted Tree model after training. 
- `Tuned_GBT`: GBT model after tuning and training. 

- `mini_sparkify_event_data.json`: subset of user activity data. (not uploaded due to data quota limit)

## Results
The findings and outcomes of this project are discussed and showcased in detail in this [blog post](https://medium.com/@Faisal_Alageel/analyzing-churn-at-sparkify-using-pyspark-6f7e3d4dc996).

It's important to note that while the model performs reasonably well, it's not flawless. While it may not achieve perfection, it effectively identifies users with a higher likelihood of churning. It's worth mentioning that one constraint I encountered was the inability to run the model on the entire dataset due to AWS tier limitations.

## Licensing and Acknowledgements
I extend my appreciation to Udacity for their generous provision of course materials and for presenting this challenging project.
