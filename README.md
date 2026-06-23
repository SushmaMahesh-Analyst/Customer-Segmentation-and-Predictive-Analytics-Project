# Customer-Segmentation-and-Predictive-Analytics-Project

A machine learning project focused on predicting customer renewal behaviour and segmenting customers based on product preferences using Decision Trees and Hierarchical Clustering in RStudio.

## Methodology
This project follows a structured machine learning workflow starting from data preprocessing to predictive modelling and customer segmentation.

## Setting up the Environment
The analysis was performed in R using packages such as rattle, rpart, tidyverse, cluster, ggplot2, knitr, kableExtra, and scales for modelling, visualization, and reporting.

## Tools & Technologies 
R Programming, Tidyverse (dplyr, ggplot2, tidyr), rpart (Decision Trees), cluster (Hierarchical Clustering), plotly (Interactive Visualisations), data preprocessing, feature engineering, statistical analysis

### 1. Data Preparation & Cleaning
Handled missing values and ensured data consistency across datasets. Relevant features were selected, transformed, and prepared for modelling and clustering analysis.

### 2. Predictive Modelling (Decision Tree)
Built a Decision Tree classification model to predict user conversion behaviour based on key attributes such as age, spending patterns, and length of relationship (LOR). The model identified the factors most strongly associated with user conversions and was evaluated using training and test datasets.

#### Model Evaluation: The model was evaluated using both training and testing datasets.
- Training Accuracy: 62%.
- Testing Accuracy: 51%.
The drop in accuracy between training and testing indicates overfitting in the initial model.

#### Model Optimization (Pruning): To reduce overfitting, the decision tree was pruned using a maximum depth constraint.
- Pruned Model Training Accuracy: 61%.
- Pruned Model Testing Accuracy: 52%.
Pruning improved generalization and reduced overfitting slightly.

### 3. Clustering & Segmentation
Applied Hierarchical Clustering to group users with similar behavioural characteristics and engagement patterns. The analysis identified distinct user segments, enabling a better understanding of customer preferences and supporting targeted marketing and retention strategies.

### 4. Cluster Profiling
Clusters were analyzed using average product ratings, age distribution, and gender distribution.
- Cluster 1: Largest segment, strong preference for D4 and D5.
- Cluster 2: Prefers D3 strongly, dislikes D5.
- Cluster 3: Strong preference for D1, declining interest in newer variants.

## Key Outcomes
- Decision tree model achieved 62% training accuracy and 51% test accuracy, indicating mild overfitting.
- Pruned model improved generalisation with 52% test accuracy.
- Three customer segments were identified using hierarchical clustering.
- Clustering produced a mean silhouette score of 0.255, indicating weak but interpretable structure.
- Segmentation supports targeted marketing and product strategy optimization, with an estimated ~5% potential revenue improvement.

## The full analysis report can be viewed here:  
https://rpubs.com/SushmaMahesh/1256386 
