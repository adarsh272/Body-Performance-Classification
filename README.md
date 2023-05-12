# Body-Performance-Classification

**Live:** https://ml-app-b4nv.onrender.com/

**Source of data:**

Kaggle
https://www.kaggle.com/datasets/kukuroo3/body-performance-data

**Problem Statement:**

Create a machine learning model that can successfully predict the body type of a person based on some of their features like blood pressure, height, weight, physical prowess etc...

**Understanding of dataset:**
1. Used Pearson's Correlation Co-efficient to find out a linear relationship (if exists) between features like body fat percentage and weight, body fat percentage and gender.
2. Identified a  linear relationship between height and weight of individuals
3. No significant outliers detected
4. No null data detected
5. The distribution of each target class is uniform and balanced
6. Plotted trend between age groups and body types: Which age group had the highest number of a particular body type?
7. Used Chi Sqaure test of independence to find out if correlation exists between gender and body type

**Performance Metrics:**

Paid more attention to reduce false negatives i.e. **Recall**

We cannot afford to identify a person as healthy when in reality they are unhealthy. This might lead to irreversible consequences.

For multi-class classification, decision tree ensembles are the best algorithms due to their feature importance technique and ability to deal with multiple classes at once.

Since random forest gave us a slightly better recall percentage, Random Forest Classifier became our final model
