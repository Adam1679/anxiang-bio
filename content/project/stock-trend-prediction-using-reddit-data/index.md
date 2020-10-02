---
title: Stock Trend Prediction using Reddit Data
date: 2020-10-02T05:41:16.134Z
draft: false
featured: false
categories:
  - ML
external_link: https://files.pushshift.io/reddit/comments/
image:
  filename: rd.jpg
  focal_point: Smart
  preview_only: false
---
- Applied PCA and sentiment analysis to extract features from 1 TB Reddit comments using MapReduce. Created cluster on AWS EMR machine and used AWS S3 bucket to store the large data.
- Trained a logistic regressing to predict the stock market trend using PySpark; obtained 65% prediction accuracy.