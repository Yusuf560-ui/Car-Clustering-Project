# Car Groupings Project
An unsupervised learning project that groups cars into distinct clusters using available features like mpg, horsepower, acceleration and many others, with KMeans and Hierarchical clustering algorithms

## Project Overview
This project experimented with KMeans and Hierarchical clustering algorithm to group cars into groups using various features from the dataset like mpg, cylinder, horsepower and many others. The aim of the project is to discover underlying patterns and characteristics of cars from the dataset inorder to group them into distinct cluster

---

## Dataset Features
- mpg: Miles per gallon of each car
- cylinders: no of cylinders
- displacement: Engine displacement of vehicles
- horsepower: Horsepower of each car
- weight: Weight of each car
- acceleration: Acceleration of each car
- model_year: Years the cars were made
- origin: Car's origin (USA, EUROPE, JAPAN)
- name: The name of the car

---

## Data preprocessing and Modelling
- The dataset inspection revealed no missing and duplicate values
- EDA with histogram and boxplot on numerical columns to visualise their distribution
- Scatterplots for multivariate analysis of numerical columns
- Feature Engineering: Dropped the "name" columns and one-hot encode
- Experimented with both KMeans and Hierarchical clustering 
- Evaluation on both algorithm with Silhoeutte score showed 4 as optimal cluster value

---

## Result and Conclusion
Decided to use the hierarchical clustering algorithm since it's the best for smaller dataset
- Cluster 0: Balanced vehicles
- Cluster 1: Fuel-efficient, low power
- Cluster 2: High efficiency, low power
- Cluster 3: Performance-oriented, low efficiency

