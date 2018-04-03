# Crimes Classification Using Different types of Support Vector Application

This data set was taken from kaggle. The motivation behind this analysis is to get a brief idea regarding a famous classifier which is Support Vector Machine. There are various kernel tricks when we are using SVMs. There are many advantages of Support vector machines as compared to tree classifier or bayseian classifiers. Tree classifiers split the data on the basis of the perpendicular ie 90 degree partition. SVMs instead can go for a angular split depending on the slope of line they want. 

SVM's use a hyperplane to classify the data. They have two types of SVM settings which we can tune by optimizing the 'C' parameter.

Soft SVM's: This type of SVM's are ideal to use as they are not very strict on data points on the area of the hyperplane. They are idea because the size of hyperplane is more . Due to the large size of hyperplane they can generalize on data and the model is not overfit.

Hard SVM's: These SVM's are very strict with the data points and usually do not allow data points to be on the hyperplane area. Due to their strict nature they are not very good at generalizing data and are prominent to overfitting.

SVM's are computationally heavy algorithms. Hence it is a rare case when we use a non linear SVM. Mostly we try to use a linear SVM . A kernel trick is another beauty of SVM where it calculates the range of models in the memory itself rather using the space!!

Have used different type of SVMs.
Linear SVM: The learning of the hyperplane in linear SVM is done by transforming the problem using some linear algebra.
Polynomial SVM : Polynomial and exponential kernels calculates separation line in higher dimension. This is called kernel trick

Pros and Cons associated with SVM
Pros:
It works really well with clear margin of separation
It is effective in high dimensional spaces.
It is effective in cases where number of dimensions is greater than the number of samples.
It uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.
Cons:
It doesn’t perform well, when we have large data set because the required training time is higher
It also doesn’t perform very well, when the data set has more noise i.e. target classes are overlapping
SVM doesn’t directly provide probability estimates, these are calculated using an expensive five-fold cross-validation. It is related SVC method of Python scikit-learn library.
