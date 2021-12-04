# Fetal-Health-Prediction-Using-Classification-Algorithms


Cardiotocography (CTG) is a frequently used diagnostic technique to monitor fetal health both during the pregnancy and in labour. The continuous CTG produces a paper recording fetal heart rate and the mother's labour contractions. The information provided is monitored with the purpose of reducing the risk of stillbirth or serious neurological injury in high-risk pregnancies. One of the main disadvantages of this monitoring method is the interpretation of the different fetal heart rate patterns, which is subject primarily to the training and experience of the physician. The creation of predictive models to classify the fetal state accurately could reduce the variability in the interpretations of CTG traces and support medical decisions. 
This project utilizes an open-source dataset available in UCI Machine Learning Repository, consisting of 2,126 instances and 21 attributes. Each instance represents measurements of fetal heart rate signals and uterine contractions using CTG. The dataset contains information corresponding to normal, suspect, and pathological fetal states, which are the three classes of the dataset. These classes were determined by three expert obstetricians for each of the instances.
The objective is to predict fetal health using classification algorithms, such as Random Forest, XGBoost, and Multi-layer Perceptron (MLP). The performance of these algorithms will be measured by calculating precision, accuracy, recall, and F-1, among others. The analyses and comparisons of the accuracy of these different algorithms are performed using Python.


Link to dataset: https://archive-beta.ics.uci.edu/ml/datasets/cardiotocography
**Methodology
**Exploratory Data Analysis**
As shown in Figure 2., the methodology for this project begins with an Exploratory Data Analysis. This first step provides descriptive statistics of the data used to create the predictive models.
Data Preparation
Based on the exploratory data analysis findings, I decided to scale six of the 21 attributes. These attributes represent different types of measurements obtained from the cardiotocography. 
The measurements were transformed from per second to an average per minute.


**Predictive Modeling**
The methodology of this project involves two different approaches. The first one uses the original imbalanced dataset. The second one considers the application of an augmentation method to work with a balanced version of the dataset. In both cases, the approach utilized cross-validation techniques to generate models from three algorithms: Random Forest, XGBoost and Multilayer Perceptron. 

**Performance Metrics and Conclusions**
Once the models were generated, I measured their performance by computing different metrics such as Accuracy, Precision, Recall and F-1 score. 
As mentioned previously, this project addresses the problem from an efficiency perspective in terms of the use of resources in public health systems, and the conclusions are developed focusing on this approach.
