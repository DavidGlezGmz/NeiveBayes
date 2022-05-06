# NeiveBayes
A Naive Bayes classifier is a probabilistic machine learning model that’s used for classification task. The crux of the classifier is based on the Bayes theorem.:

![image](https://user-images.githubusercontent.com/86708470/167204335-c29039e8-a629-480f-a03a-1ebabce2771c.png)

Using Bayes theorem, we can find the probability of A happening, given that B has occurred. Here, B is the evidence and A is the hypothesis. The assumption made here is that the predictors/features are independent. That is presence of one particular feature does not affect the other. Hence it is called naive.
(From Towards Data Science / Rohith Gandhi: https://towardsdatascience.com/naive-bayes-classifier-81d512f50a7c).

### Use Case
A database is used with the registration of "height" and "weight" of 1000 people. The classification (supervised) is binary 0 or 1 depending on whether it is male or female.

![image](https://user-images.githubusercontent.com/86708470/167209030-c4f5492a-d757-43f4-ac6a-230f67616319.png)
![image](https://user-images.githubusercontent.com/86708470/167208995-64b81a1a-2d07-4160-912a-f7861f3c89d9.png)
