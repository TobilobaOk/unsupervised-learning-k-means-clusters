# unsupervised-learning-k-means-clusters


# Objective:

To explore and group similar Facebook live videos using K-Means clustering based on features such as likes, shares, comments, and other engagement metrics.

# Background:

Live streaming has become a powerful tool for small businesses to promote and sell products directly to audiences. Understanding patterns in engagement can help improve strategy.

# Problem Statement:

The dataset lacks predefined labels, so we aim to identify distinct clusters of Facebook Live sessions that exhibit similar viewer behavior.

# Dataset Overview


**Source:** UCI Machine Learning Repository

**Data Description:** The dataset contains 7050 Facebook live session records with the following key features:

**status_type:** Type of status (live, photo, video, etc.)

**num_reactions, num_comments, num_shares:** Engagement metrics

**num_views:** Number of views

**num_likes, num_loves, num_wows, etc.:** Reaction breakdown

**Target:** Unsupervised (no target column)

# EXPLORATORY DATA ANALYSIS

We can see that there are 7050 instances and 16 attributes in the dataset. In the dataset description, it is given that there are 7051 instances and 12 attributes in the dataset.So, we can infer that the first instance is the row header and there are 4 extra attributes in the dataset. Analysis the following to prepare the data:

Handled missing values

Drop redundant columns

Trimmed dataset by dropping status_id and status_published

Normalized/standardized numerical features

Convert category variable into integers

One-hot encoding for categorical data 

#METHODOLOGY

**Unsupervised Learning Technique:** K-Means Clustering

**Reason for Choice:**

Simple and effective for discovering groupings in unlabeled data

Works well with numerical and engagement-based features

**Steps Taken:**

Declare feature vector and target variable

Feature scaling

Fitting K-means model

K-mean model parameters study(inertial)

Check quality of quality of weak classification by the  model

Used elbow method to find optimal number of cluster

K-mean model with different clusters to achieve more relatively high accuracy.

