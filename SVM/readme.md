**SVM - Support Vector Machine Notes** 
It is a powerful method for classification (**supervised learning**)

***What is Supervised Machine Learning?***

 - Supervised learning is when you train a machine learning model using labelled data. It means that you have data that already have the right classification associated with them. One common use of supervised learning is to help you predict values for new data.
 - With supervised learning, you'll need to rebuild your models as you get new data to make sure that the predictions returned are still accurate.


***What is SVM?***

Support vector machines are a set of supervised learning methods used for classification, regression, and outliers detection.
SVMs are different from other classification algorithms because of the way they choose the decision boundary that maximizes the distance from the nearest data points of all the classes.
The decision boundary created by SVMs is called the maximum margin classifier or the maximum margin hyper plane.

**Linear SVM algorithm is better than some of the other algorithms, like k-nearest neighbors, because it chooses the best line to classify your data points. It chooses the line that separates the data and is the furthest away from the closet data points as possible**

***Types of SVM:***

-   **Simple SVM:** Typically used for linear regression and classification problems.
-   **Kernel SVM:** Has more flexibility for non-linear data because you can add more features to fit a hyperplane instead of a two-dimensional space. **(What I've used)**
**Kernel SVM :**
SVM algorithms use a set of mathematical functions that are defined as the kernel. The function of kernel is to take data as input and transform it into the required form.
“Kernel” is used due to a set of mathematical functions used in Support Vector Machine providing the window to manipulate the data.
**Linear Kernel :** 
The linear kernel works really well when there are a lot of features, and text classification problems have a lot of features. Linear kernel functions are faster than most of the others and you have fewer parameters to optimize.
Here's the function that defines the linear kernel:
```f(X) = w^T * X + b```
In this equation, **w** is the weight vector that you want to minimize, **X** is the data that you're trying to classify, and **b** is the linear coefficient estimated from the training data.

**What is a Confusion Matrix?**
Confusion Matrix is a performance measurement for machine learning classification.		 ![enter image description here](https://miro.medium.com/max/640/1*Z54JgbS4DUwWSknhDCvNTQ.webp)
