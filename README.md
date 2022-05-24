# NeiveBayes
A Naive Bayes classifier is a probabilistic machine learning model that’s used for classification task. The crux of the classifier is based on the Bayes theorem.:

![image](https://user-images.githubusercontent.com/86708470/167204335-c29039e8-a629-480f-a03a-1ebabce2771c.png)

Using Bayes theorem, we can find the probability of A happening, given that B has occurred. Here, B is the evidence and A is the hypothesis. The assumption made here is that the predictors/features are independent. That is presence of one particular feature does not affect the other. Hence it is called naive.
(From Towards Data Science / Rohith Gandhi: https://towardsdatascience.com/naive-bayes-classifier-81d512f50a7c).

### Use Case
A database is used with the registration of "height" and "weight" of 1000 people. The classification (supervised) is binary 0 or 1 depending on whether it is male or female.

![image](https://user-images.githubusercontent.com/86708470/167209030-c4f5492a-d757-43f4-ac6a-230f67616319.png)
![image](https://user-images.githubusercontent.com/86708470/167209194-3a8e2bc7-0cc6-468f-85e0-8530d6affcce.png)


## MNIST handwritten image classification with Naive Bayes
MNIST dataset with 60000 train data and 10000 test data. It is one of the most commonly used datasets for Machine Learning. Each image in both training and test set is a grey scale image of dimension 28x28 pixels. Is a large database of handwritten digits from 0–9.

![image](https://user-images.githubusercontent.com/86708470/170129206-5e202ee2-4c9d-49be-9e09-108d851b30a7.png)

The problem involves building a Naive Bayes classifier on MNIST dataset. Results include confusion matrix, accuracy of each digit, and over accuracy. It also assumes that probability of each pixel is a Gaussian distribution and the probability of each digit is equal.

### Results.
![image](https://user-images.githubusercontent.com/86708470/170129421-9f932878-5e09-4bfe-b590-3f606196efe7.png)
