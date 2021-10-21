# Fetal-Health-Prediction-Using-Classification-Algorithms

Cardiotocography (CTG) is a frequently used diagnostic technique to monitor fetal health both during the pregnancy and in labor. 
The continuous CTG produces a paper recording fetal heart rate and the mother's labour contractions. The information provided is 
monitoring with the purpose of reducing the risk of stillbirth or serious neurological injury in high-risk pregnancies. 
One of the main disadvantages of this monitoring method is the interpretation of the different fetal heart rate patterns, 
which is subject primarily to the training and experience of the physician. The creation of predictive models to classify 
the foetal state accurately could reduce the variability in the interpretations of CTG traces and support medical decisions. 

For this project, an open-source dataset available in UCI Machine Learning Repository will be used, which consists of 
2,126 instances and 21 attributes. Each instance represents measurements of fetal heart rate signals and uterine contractions 
using CTG. The dataset contains information corresponding to normal, suspect, and pathological fetal states, 
which correspond to the three classes of the dataset. These classes were determined by three expert obstetricians for each of the instances.
The objective of this project is to predict fetal health using classification algorithms, such as Multi-layer Perceptron (MLP), 
Random Forest, and XGBoost. The performance of these algorithms will be measured by calculating precision, accuracy, recall, and F-1 score. 
The analyses and comparisons of the accuracy of these different algorithms will be performed using Python.

Link to dataset: https://archive-beta.ics.uci.edu/ml/datasets/cardiotocography
