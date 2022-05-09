# P6 - Microorganism Classification
 Microorganisms classification using KNN, Decision Tree and Random Forest.

# 1. Project Summary

This project is carried out to implement Traditional Machine Learning approach on Microorganism classification using KNN, Decision Tree and Random Forest Algorithm. The focus of the model training is to predict the type of Microorganisms based on the size and shape of the microorganisms. The dataset is obtained via this [LINK](https://www.kaggle.com/datasets/sayansh001/microbes-dataset?resource=download). The dataset consist of 10 classes of microorganisms.

# 2. IDE and Framework

The project is built with Jupyter Lab as the main IDE. The main frameworks used in this project are Pandas, Numpy, Matplotlib, Seaborn and Scikit-learn.

# 3. Methodology

The methodology of this project is first by doing data cleaning. The dataset is pretty simple and straightforward and not much of data cleaning is required.  The data is then visualize and analysed to gain first insight. Then, the target is converted to numerical encoding as below. The data is splitted to the ratio of 80:20 for train and test data respectively. The model algorithm used in this project are KNN, Decision Tree and Random Forest that are well known for classification problems.

Aspergillus sp (0),
Diatom         (1),
Penicillum     (2),
Pithophora     (3),
Protozoa       (4),
Raizopus       (5),
Spirogyra      (6),
Ulothrix       (7),
Volvox         (8),
Yeast          (9),

## 3.1 Input Pipeline

The dataset is in the format of csv file and contains information of sizes and shape of the microrganism with the label of 10 type of microorganism. The dataset is split into train and test data using train_test_split from Scikit-learn. 

## 3.2 Model Pipeline

The model algorithms used are from Scikit-learn which are widely used for classification problems. The model used for this purpose are:-
1. KNN
2. Decision Tree
3. Random Forest

# 4. Result

## 4.1 KNN Model

KNN is type of supervised learning that use for the multiclass classification problem. KNN algorithm works by calculating the "datapoint" distance between its neighbors. The working mechanism of KNN can be illustrated as in figure below. The result of KNN algorithm can be represent by using confusion matrix below. The f1 score is 97%.

![KNN Confusion Matrix](https://user-images.githubusercontent.com/100177902/167408451-75f7f8d7-e7a6-47c5-bb2d-122649aeb16a.png)

## 4.2 Decision Tree

Decision Tree is a supervised machine learning algorithm that can be used in both classification and regression problems. The model is build in such a way of a tree structure with decision nodes and leaf nodes. A decision node consists of two or more branches. Leaf node represents the target values or decision. A topmost decision node is the root node. The result of Decision Tree algorithm can be represent by using confusion matrix below. The f1 score is 99%.

![Decision Tree Confusion Matrix](https://user-images.githubusercontent.com/100177902/167408997-32cb4621-fb62-46c8-9794-a05ed021ef71.png)

## 4.3 Random Forest

Random Forest is also type of supervised machine learning algorithm that also can be used in both classification and regression problems. Random forest is an esemble that constructs many decision trees during the training. It predicts the mode of the classes for classification tasks and mean prediction of trees for regression tasks. The result of Random Forest algorithm can be represent by using confusion matrix below. The f1 score is 100%.

![Random Forest Confusion Matrix](https://user-images.githubusercontent.com/100177902/167409272-c25f4bc7-d800-482b-bcdf-ec606c2fd210.png)

# 5. Conclusion

There are many machine learning algorithm that can be used for predictions. In this project, three types of ML algorithm used gave different accuracy result. The highest accuracy can be seen from Random Forest algorithm, then Decision Tree algorithm and least accurate is from the KNN algorithm with 100%, 99% and 97% accuracy respectively. However three of the ML algorithm used managed to achieve high accuracy score despite the imbalance data between the class of the microorganism.


