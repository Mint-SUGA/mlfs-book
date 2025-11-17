# Air Quality Prediction
Authors: Yuting Cui, Man Zhang - Group 100

## Dashboard
[Dashboards for Air Quality](https://mint-suga.github.io/mlfs-book/)

## Description
This project realizes an air quality (PM2.5) prediction in London based on its history weather and air quality. Data sources are from aqicn.org and open-meteo.com.

We use HopsWorks as platform for maintaining feature groups and training models. With the trained model, we predicte the air quality in the future 7 days.

A lagged data feature is included with average air quality in the past days. When making predictions for days without a past-3-day history, predicted air quality data for those days will be used instead.

The project also includes two more sensors in central London, Batterseaparkroad and Nineelmslane.