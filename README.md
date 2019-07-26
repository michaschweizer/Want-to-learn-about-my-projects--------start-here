# How to learn more about my projects

## Introduction

Thank you for your interest in my work as a data scientist. On this github account, I created several repos that showcase some data-related projects I completed. These repos should give you an idea of my skills, experience, and passions.

## Topics covered
I included multiple data-related topics that I explored through various projects in the last couple months. The projects showcased originated from several sources:
* Course work for my Masters in Business Analytics at GWU
* Projects conducted in my role as a Data Scientist at Data Society
* Ideas collected in my role as a Management Consultant at The Boston Consulting Group
* Entrepreneurial initiatives
* Personal topics of interest

The projects showcased include individual projects as well as group projects.


Topics covered include the following:

| Topic | Description |
|---|---|
| [Machine Learning](1-keras-and-tensorflow) | Deep Learning using Keras; ML on structured data using h20.ai |
| [Big Data](2-pytorch) |Image classification with Spark running on an AWS EMR cluster|
| [SQL Databases](3-transfer-learning-model) | Building star schema data warehouse and querying data using SQL|
| [Visualization](3-transfer-learning-model) |RShiny; Network visualization with R; Python Leaflet|
| [Web Scraping](3-transfer-learning-model) |Scraping tabular data from websites|
| [Excel Modeling](3-transfer-learning-model) |Monte Carlo simulations; Financial modelling|
| [Effective Communication](3-transfer-learning-model) |Presentation created for WMATA; Article written for Elite Daily|
| [Creating Business Value](3-transfer-learning-model) |Takeaways from I-Corps entrepreneurship program|



In regards, we chose the 'Aerial Cactus Identification' (https://www.kaggle.com/c/aerial-cactus-identification), where we were to identify if an image has a specific type of cactus from different aerial angles. 

### Machine Learning

This repo showcases two ML projects. Deep Learning using Keras is a project conducted as part of the Aerial Cactus Identification competition on Kaggle. 



## Approaches

In order to explore different approaches and packages offered for image recognition, we made multiple submission to Kaggle Competition using different methods. 

The approaches that we've taken are as follows:

| Contents |
|---|
| [Section 01: Keras and Tensorflow](1-keras-and-tensorflow) |
| [Section 02: PyTorch](2-pytorch) |
| [Section 03: Transfer Learning Model](3-transfer-learning-model) |


Through tackling the same project with different approaches, we were able to compare the advantages and disadvantages of each of the approaches such as the total time required for running the model, different options we can set for each of the methods. This in conclusion, allowed us to better understand what approaches we should be taking for other neural network projects in the future according to the different project conditions and requirements. 


## Results and Conclusion

For all of the different approaches made, the results were as follows:

The result from the image above is from submitting the keras model, which scored the highest submission AUC among the three models. 
Detailed results from each of the models can be found below. 

| Model | Test/Valid Accuracy | Test AUC (Kaggle Submission) |
|:-----: | :-----: | :-----: |
| Keras and Tensorflow| 95.21% | 0.9992|
|PyTorch | 99.48% | 0.9990 |
|Transfer Learning Model | 97.7% |0.991 |

We can see that models from scratch using Keras or PyTorch scored higher than transfer learning models by a small difference. We councluded that this is because of the nature of the project, which was relatively specific and thus the generic trained model did not perform as well. 

Since the Keras and Tensorflow Model which was trained purely on the training data gave us the best test AUC, we chose to submit this model to the Kaggle competition. Our rank was 514 out of 1092 submissions.

![Kaggle results](https://github.com/netinupur/machine-learning-project/blob/master/kaggle_leaderboard.png)

## Further Explorations

We were constantly faced with the problem of the multiplicity of good models and not enough computational power to find the best model. We approached this problem as best as we could with random grid searches and learning from previous Kaggle kernels. However, maybe we could further improve our performance by :

* learning to build neural networks using Spark on clusters to run a wider grid search
* understand samples of our data better to set better ranges for our hyperparameters
* learning how to use multiple GPU for a more efficient data processing into the model
