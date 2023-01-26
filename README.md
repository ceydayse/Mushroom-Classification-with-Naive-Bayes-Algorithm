# Mushroom-Classification-with-Naive-Bayes-Algorithm
In this project, it is aimed to make classification using Naive-Bayes algorithm with Mushroom Data Set. 

The Naive-Bayes algorithm is purely probabilistic, meaning Bayesian learning refers to problem solving involving machine learning with a probabilistic approach. In this project, we will present the results we obtained with this algorithm. 

Naive Bayes is a classification algorithm that utilizes Bayes' theorem to predict the probability of a certain class or category given a set of features or attributes. It is a probabilistic algorithm, which means that it is based on the probability of certain events occurring. 

One of the main advantages of Naive Bayes is that it is computationally efficient and easy to implement. It also requires a small amount of training data, which makes it a good choice for applications where labeled data is limited. Additionally, it can handle missing data and can be used with both discrete and continuous data.

The materials we used in our project are given below:
1) Data set containing information such as cap-shape, cap-color, habitat of mushrooms
Dataset: https://www.kaggle.com/datasets/uciml/mushroom-classification 
2) Data analysis and visualization software such as Python language, Pycharm IDE, Rapidminer
3) Libraries and packages to implement the Naive Bayes algorithm

# TOOLS
In our project, we will use the RapidMiner program developed for machine learning and predictive analysis purposes. For coding, we will code on Python language with Pycharm IDE.

![image](https://user-images.githubusercontent.com/73853133/214951527-05390f45-f945-44d4-bb8a-e9232a497aae.png)

The table we get when we upload our mushroom data to Rapidminer is given
 
In Rapidminer, we add the read CSV operator from the operators section in the design section. Then we add the naive bayes operator by typing Naive Bayes in the search section. Finally, we establish connections between operators by adding cross validation.
 
Then we create a training and testing section to set up the cross validation. We add the naive bayer operator to the train part and the apply model and performance operators to the testing part. When we start the execution, we reach the conclusion.
 
When we click on the performance section on the program, we can see the results. Our accuracy value in rapidminer is 99.58%. We are given our true e and true p values. The Recall value is a metric that shows how many of the transactions we need to predict as positive are positive.
 
We can also look at ROC-AUC graphs in rapidminer program. ROC-AUC curves are a performance metric for classification problems at various thresholds. ROC is a probability curve and the area under it, AUC, represents the degree or measure of separability.
 
# CODES

First of all, we import the following libraries.
 ![image](https://user-images.githubusercontent.com/73853133/214951937-962f4f73-fe2e-4432-af1e-900fdfe7dcc7.png)

Then we download and import our data set.
 ![image](https://user-images.githubusercontent.com/73853133/214951927-355641eb-5d6b-441c-9f72-5cbd7f326e5d.png)

Our data consists of missing data with '?' as value. All the missing values are from a single column. We delete them with the following code.

![image](https://user-images.githubusercontent.com/73853133/214951904-93790bbc-44d9-41e1-96b6-b5744b19d8bb.png)

![image](https://user-images.githubusercontent.com/73853133/214951863-78c23f47-2ecc-45b8-acd9-bfbeecce9349.png)

![image](https://user-images.githubusercontent.com/73853133/214951841-94e8b90f-e92c-47e3-ab88-8c990bb1d56e.png)

We write our probability code for probability. Then we define classify. In this way, we can classify mushrooms. Then we split our data into training and test datasets. We reach our data by using the Loc command for train and test. We print the results to check our accuracy.

![image](https://user-images.githubusercontent.com/73853133/214951821-34880147-ea80-46fe-8fa0-bf2872d2c69b.png)

# Results

The results of our project are given below. 
When we run the code, training accuracy 99.59% 
![image](https://user-images.githubusercontent.com/73853133/214952022-2dc4afa5-7585-4def-a39d-c7bc4719428a.png)

# Results
In this project, we tried to classify mushrooms using the Naive Bayes classification algorithm with the Mushroom Dataset. The program has successfully achieved its purpose. In our Run result, the training accuracy was 99.59%. Naive Bayes classification algorithm is relatively simple and computationally efficient, making it a good choice for large datasets or real-time applications. Additionally, it can handle missing data and can be easily trained using a small amount of labeled data. 
In conclusion, Naive Bayes is a fast and simple algorithm that can be used for classification tasks and is particularly well suited for text classification. It performs well with small data set and does not require large amount of data for training.


