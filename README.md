#### AaltoProject
This repository contains all the projects for Masters in Machine Learning and Data Mining at Aalto University (2017-19).

1. Visual Explanation for Deep Learning
Imagenet classification with deep convolutional neural networks [3] was the first paper that sparked a huge interest in deep convolutional neural networks. After the success of Alexnet, researchers started to apply deep learning to different areas and gained a huge increase in performance. But, deep learning models are black-box models which are difficult to understand. As they gain more importance day by day, the need to understand the working of deep learning model grows. In this project, we will discuss a few techniques that offer to explain the working of convolutional neural networks.

2. Comparison of Sample Efficient Reinforcement Learning Algorithms
In recent years, the application of reinforcement learning (RL) algorithm to learn dynamic systems have seen a huge improvement with deep learning. Model-based RL algorithms try to learn the model of the environment and maximize the reward with respect to the model whereas model-free RL maximizes the reward with respect to interactions from the environment. In this report, we compare model-free RL algorithm Probabilistic Inference for Learning Control (PILCO) and it’s deep learning variant called Deep PILCO to Soft Actor-Critic (SAC) which is a model-based RL algorithm. We present our findings with respect to the continuous control cart-pole swing-up task.

3. Comparison of Time Series Models in Stan
Time series is a series of data indexed in time order. Time series are used in multiple areas such as financial market, weather forecasting and other engineering applications. Time series analysis is used to analyze the time-series data to find meaningful insights. Time series forecasting is using historical time series data to predict future events.

In this notebook, we will compare the different time-series model for forecasting. We briefly discuss the relevant concepts to time-series forecasting and then discuss the assumptions with a different model in section 2. Then we take a look into different priors in section 3 followed by the Stan implementation of the model in section 4. We check the convergence of the sampling for these models in section 5 and perform posterior predictive checking in section 6. We do a model comparison using LOO-CV in section 7 followed by sensitivity analysis in section 8. Finally, we conclude in section 9.

We use Air Passengers dataset to compare the different time series model. This dataset has the number of air passengers per month from 1949 to 1960. We will use data from 1949 to 1950 as the training set for our models and 1959 to 1960 as a test set. Our goal is to predict the number of passengers who will travel from the year 1959 to 1960.

4. Spectral Graph Partitioning
Graph Partitioning is very useful for solving problems like load balancing, VLSI layout and matrix multiplication. It is the problem of partitioning a graph G into smaller components according to the given requirements. In this project, we implement the spectral graph partitioning algorithm using normalized and unnormalized Laplacian and evaluate it on nine graph datasets. We compare the results of algo- rithm to make well-balanced partitions using the competition criteria. We conclude by presenting our findings and suggesting improvements for future work.

5. Using Voting Classifier and Sampling for Unbalanced Classification Problem
Music genre classification is the task of assigning genres to music. Not only, music can belong to more than one category but there can be a lot of variations based on artist, geographical locations etc
which can make it difficult to identify the genre of music based on acoustic properties. We were provided with a class imbalanced dataset of music meta-features. We reduce the dimension of the dataset by removing collinearity. Then we resample from the original dataset to create a new dataset with balanced classes. We compare several classifiers using cross-validation and finally employ a voting classifier to make the prediction. We achieve a test accuracy of 96% on the training data and 65% accuracy on Kaggle.

6. Predicting age using brain cortical thickness data
Brain structure varies between people in an organized fashion. Inter-individual differences in different parts of the brain can covary which is called structural covariance. It has been claimed at times that structural covariance can arise from some sort of physical connectivity of white matter or functional connectivity of neurons.

We used physical connectivity a.k.a thickness to form networks which are used to study structural covariance with respect to age. The aim of the project was to investigate whether the brain networks
generated using cortical thickness data are better in predicting the age of the subject compared to only the data itself.

7. Fake News Detection
Fake news has gained notable attention after the US 2016 presidential election. The misinformation spread by fake news divides people into polarized groups on social media. The polarized groups tend to engage in the content within their filter bubble and dismiss the opinions of other groups. Such conditions can harm democracy and lead to echo chambers which reinforce political extremism.

This project focuses on using word-level embeddings to classify and understand fake news. In this project, we also use LIME which stands for local interpretable model-agnostic explanations. LIME explains the prediction of any black-box model by approximating it locally using a simpler model. We compare Naive Bayes Classifier, K-Nearest Neighbors, Random Forest, Support Vector Machines etc.

8. Disproportionality analysis
Itemset mining is used to identify frequent items in dataset having minimum support specified by the user. The problem is also sometimes viewed as “association rule mining” to discover rules that show how variables are associated in a dataset. The main objective of this project is to identify an adverse drug event which is an injury incurred to the patient due to the usage of the drug.

9. Neural Network Language Models
The topic of our project was to evaluate the performance of artificial neural
networks at language modelling by comparing it to the n-grams method. We therefore first ran trough several scientific papers explaining what language modelling consists of and what were the different methods to approach this problem, including different types of n-grams and neural networks. Then, we set up a series of experiments for n-grams and neural networks and produce results on a given data set.This report presents a review of the literature we read, the setting up of the experiments and their results.
