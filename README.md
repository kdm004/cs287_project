# Predictive Modeling of Childhood Internalizing Disorders with KID Study Data
This repo houses our course project for the course Data Science I (CS 287) at the University of Vermont

# Goal
Here, we create multiple pipelines to train and test machine learning models to classify children with anxiety, ADHD, and depression based on data obtained from wearable sensors during stress-inducing tasks. 

# Challenges
The primary challenges encountered in this study were noted to be a lack of data volume and a class imbalance. The imbalanced distribution of classes in the data set, i.e. diagnoses of anxiety, ADHD, and depression, led to the use of SMOTE to generate synthetic data via the small training data set, which may not have contained sufficient data to generate information truly representative of the real-world. We identify this as one of the notable factors that led to low AUC values for our tree-based models that attempted to classify anxiety. 

