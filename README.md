# Data-Mining-Machine-Learning
### Human Activity Recognition Analysis using machine learning methods:

#### Activities are recorded both in our mobile phones and smart watches via accelerometer monitoring data. These data can then be used in numerous ways to predict all kinds of health problems, bad habits and etc. Finding the exact kind of activity using the accelerometer data is a difficult task, let alone using these designated activities to identify a bad habit or possible risks. I'll be using machine learning techniques to verify these activities based on their accelerometer data and then it can be used to map new examples (predict user activities) and be analyzed further.

### Background:

#### Activity recognition is a significant technology in ubiquitous computing because it can be applied to many real-life, human-centric problems such as eldercare and healthcare. Ubiquitous computing (pervasive) is the growing trend towards embedding processors in everyday objects so they can monitor and pass on information. Successful research has so far focused on recognizing simple human activities.
#### The Heterogeneity Dataset for Human Activity Recognition from Smartphone and Smartwatches is a dataset planned to benchmark human activity recognition algorithms (classification, automatic data segmentation, sensor fusion, feature extraction, etc) containing sensor heterogeneities.
#### The files in this archive contain all the samples from the activity recognition experiment. The dataset contains the readings of two motion sensors commonly found in smartphones' recorded while users executed activities scripted in no specific order carrying smartwatches and smartphones.

### Data sources:

#### This is a documentation for the Heterogeneity Dataset for Human Activity Recognition (HHAR) from Smartphones and Smartwatches from the public repository:
#### https://archive.ics.uci.edu/ml/datasets/Heterogeneity+Activity+Recognition+Data+Set
#### or the personal Website: http://cs.au.dk/~allans/heterogenity/
#### The data is split into 4 files in total divided by device (phone or watch) and sensor (gyroscope and accelerometer). The files for phones are: Phones_accelerometer.csv, Phones_gyroscope.csv for the accelerometer and gyroscope respectively, and for the Watch_accelerometer.csv, Watch_gyroscope.csv for the accelerometer and gyroscope as well.

### Algorithms:

#### In the project, I am using K-means, KNN, LDA, SVM, Naive Bayes, Random Forest, Boosting and Bagging to make the data analysis and evaluate the results with the provided labels. Then establish a predictive model to make further analysis on the activities based on raw data. I also could evaluate the algorithms on their efficiency (time and correctness).

### Description:

#### The MHEALTH (Mobile HEALTH) dataset comprises body motion and vital signs recordings for ten volunteers of diverse profile while performing several physical activities. Sensors placed on the subject's chest, right wrist and left ankle are used to measure the motion experienced by diverse body parts, namely, acceleration, rate of turn and magnetic field orientation. The sensor positioned on the chest also provides 2-lead ECG measurements, which can be potentially used for basic heart monitoring, checking for various arrhythmias or looking at the effects of exercise on the ECG.

#### Here we import these datasets and combine them together. Then we test the accuracy of activity set labels (the 24th attribute comprising 12 different activities) generated using  popular machine learning algorithms mentioned earlier and compare their usability and effectiveness in this case. The detailed process is explained below.
