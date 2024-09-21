# Multi-Organ Dysfunction Syndrome (MODS) Prognosis Dataset on GitHub

## Introduction

Multi-Organ Dysfunction Syndrome (MODS) is a severe and complex medical condition characterized by the simultaneous failure of multiple organs. It is a leading cause of death in critically ill patients, with mortality rates ranging from 50% to 80%. The prognosis of MODS remains challenging due to its complex and multifaceted nature.

## Objective of the Dataset

The primary objective of this dataset is to provide a comprehensive resource for the study of MODS. The dataset includes patient data from various clinical settings, encompassing demographic information, clinical measurements, laboratory test results, and organ function scores. This rich dataset enables researchers to develop machine learning models for prognosis prediction and to identify patterns and associations within the data that can contribute to a better understanding of MODS.

## Machine Learning and its Algorithms Used

Machine learning algorithms have proven to be powerful tools for analyzing complex datasets and extracting meaningful insights. In this project, we employ several machine-learning algorithms to analyze the MODS dataset:

### Data Preprocessing: Handling Missing Values

Missing values are a common challenge in medical datasets. To address this issue, we employ interpolation techniques such as spline interpolation and nearest neighbour interpolation. These techniques estimate missing values based on the available data, ensuring complete and consistent data for further analysis.

### Prognosis Prediction: Logistic Regression and Random Forest

Logistic regression is a statistical method that models the probability of a patient developing MODS. It helps identify the most significant factors contributing to MODS onset. By analyzing the coefficients of the logistic regression model, we gain insights into the relative importance of different variables in predicting MODS.

Random forest, an ensemble machine learning algorithm, is employed to improve the accuracy of MODS prognosis prediction. Random forest combines multiple decision trees to generate a more robust and reliable prediction model. By combining the strengths of individual decision trees, random forest reduces the risk of overfitting and improves the overall prediction performance.


### Data Visualization: Heatmaps

The MODS dataset includes many variables, making it challenging to visualize and interpret the relationships between these variables. We utilize Seaborn, a data visualization library built on top of Matplotlib to address this challenge. Seaborn provides a powerful tool for creating informative and aesthetically pleasing heatmaps that represent the voids in the dataset. Heatmaps allow us to quickly identify patterns and associations within the data, facilitating a deeper understanding of the complex relationships between variables.

Heat map representation of data with missing values

![download (3)](https://github.com/Prog-cast/MOD-dataset/assets/91456061/191ac769-0332-48d7-90f3-8fed63a9f1a2) 

After using the Interpolation method Heat Map representation



![image](https://github.com/Prog-cast/MOD-dataset/assets/91456061/cf1dc255-ffea-4b30-96a3-96aaa1354e32) 


### Pie Chart

![image](https://github.com/Prog-cast/MOD-dataset/assets/91456061/2beda42f-6d61-44b3-ae0a-b22db5126033)

### Confusion Matrices

![image](https://github.com/Prog-cast/MOD-dataset/assets/91456061/6ab37d68-7a01-4ffa-b22a-7b23aee7e6c1), ![image](https://github.com/Prog-cast/MOD-dataset/assets/91456061/c23e56f7-d54d-4969-b472-65ab5ee82f16)







## Precision and Accuracy

1) The precision is the fraction of positives that were correctly identified. In this case, 100% of the positives were correctly identified as positives (precision of 1.00 
   for class N and 0.75 for class Y).

2) The recall is the fraction of positives that were found. In this case, 50% of the positives were found (recall of 0.50 for class N and 1.00 for class Y).

3) The f1-score is a measure of the balance between precision and recall. It is the harmonic mean of precision and recall, which means that it takes both precision and 
   recall into account. In this case, the f1-score is 0.67 for class N and 0.86 for class Y.

4) The accuracy is the fraction of all correct predictions. In this case, 80% of the predictions were correct.

5) The macro average precision, recall, and f1-score are the unweighted averages of the precision, recall, and f1-score for each class. In this case, the macro average 
   precision is 0.875, the macro average recall is 0.75, and the macro average f1-score is 0.8077.

6) The weighted average precision, recall, and f1-score are the weighted averages of the precision, recall, and f1-score for each class where the weights are the support for each class. In this case, the weighted average precision is 0.85, the weighted average recall is 0.80, and the weighted average f1-score is 0.8242.

   ![image](https://github.com/Prog-cast/MOD-dataset/assets/91456061/27f9720c-df95-4d7d-8470-764682e4e330)


## Summary

The MODS dataset on GitHub provides a valuable resource for studying the complex syndrome of Multi-Organ Dysfunction Syndrome. By employing machine learning algorithms, we can gain insights into the prognosis of MODS and identify factors that contribute to its development. Using interpolation, logistic regression, and random forest algorithms has shown significant improvement in prognosis prediction accuracy. 

 ![image](https://github.com/Prog-cast/MOD-dataset/assets/91456061/27f9720c-df95-4d7d-8470-764682e4e330)

## Conclusion

This project demonstrates the power of machine learning in analyzing complex medical datasets and extracting meaningful insights. By combining data preprocessing, machine learning algorithms, and data visualization techniques, we can gain a deeper understanding of Multi-Organ Dysfunction Syndrome and improve the prognosis of critically ill patients.
