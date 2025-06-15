# EVApp Passive Sensing Data Analysis

This repository contains the data processing and analysis code for the study on **user engagement and dropout prediction in a long-term passive sensing mobile application (EVApp) for electric vehicle (EV) users**.

## Background

Mobile passive sensing apps have great potential for continuous health monitoring but suffer from high user dropout rates, limiting their effectiveness. This study analyzes behavioral logs and sensor data from two experimental batches of EVApp users to:

- Investigate patterns of user participation and dropout
- Develop early-warning models for dropout prediction
- Identify usage trends and feature engagement within the app

## Dataset

The dataset includes sensor event logs collected passively from Android smartphones of 174 EV users (Batch 1: 66 users, Batch 2: 108 users). Data sources include:

- Screen Unlock events (`source_3`)
- App Resume events (`source_5`)
- Light Sensor data (`source_12`)
- Connectivity status ('source_16')
- Battery Status ('source_17')
- Gesture and interaction events (`source_18`)
- Permission_Access ('source_21')

User dropout labels are based on data submission patterns over a 6-week period.
