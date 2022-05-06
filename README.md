# P6 - Microorganism Classification
 Microorganisms classification using KNN, Decision Tree and Random Forest.

# 1. Project Summary

This project is carried out to implement Traditional Machine Learning approach on Microorganism classification using KNN, Decision Tree and Random Forest Algorithm. The focus of the model training is to predict the type of Microorganisms based on the size and shape of the microorganisms. The dataset is obtained via this [LINK](https://www.kaggle.com/datasets/sayansh001/microbes-dataset?resource=download). The dataset consist of 10 classes of microorganisms.

# 2. IDE and Framework

The project is built with Jupyter Lab as the main IDE. The main frameworks used in this project are Pandas, Numpy, Matplotlib, Seaborn and Scikit-learn.

# 3. Methodology

The methodology of this project is first by doing data cleaning. The dataset is pretty simple and straightforward and not much of data cleaning is required.  The data is then visualize and analysed to gain first insight. Then, the target is converted to numerical encoding as below. The data is splitted to the ratio of 80:20 for train and test data respectively. The model algorithm used in this project are KNN, Decision Tree and Random Forest that are well known for classification problems.

microorganisms  Target    Count
Aspergillus sp  0         3888
Diatom          1         1818
Penicillum      2         1080
Pithophora      3         1350
Protozoa        4         3888
Raizopus        5         2552
Spirogyra       6          611
Ulothrix        7         7420
Volvox          8         4320
Yeast           9         3600

## 3.1 Input Pipeline

The dataset is in the format of csv file and contains information of sizes and shape of the microrganism with the label of 10 type of microorganism. The dataset is split into train and test data using train_test_split from Scikit-learn. 

## 3.2 Model Pipeline

The model algorithms used are from Scikit-learn which are widely used for classification problems. The model used for this purpose are:-
1. KNN
2. Decision Tree
3. Random Forest

# 4. Result

## 4.1 KNN Model
