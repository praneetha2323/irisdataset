<h1>PRINCIPAL COMPONENT ANALYSIS</h1>

* Principal component analysis (PCA) is a technique used for reducing the dimensionality of such datasets, increasing interpretability. At the same time minimizing information loss. It does so by creating new uncorrelated variables that successively maximize variance.
* PCA is mostly used as a tool in exploratory data analysis and for making predictive models. It is often used to visualize genetic distance and relatedness between populations. PCA is either done by singular value decomposition of a design matrix or by doing the following 2 steps:

**1.calculating the data covariance matrix of the original data.**

**2.performing eigenvalue decomposition on the covariance matrix.**

<h3>APPLICATION OF PCA:</h3>
>1. Quantitative finance-here,principal component analysis can be directly applied to the risk management of interest rate derivative portfolios
>2. Neuroscience-A variant of principal components analysis is used in neuroscience to identify the specific properties of a stimulus that increase a neuron's probability of generating an action potential.

<h3>ADVANTAGES OF PCA:</h3>     
>1. Removes Correlated Features
>2. Improves Algorithm Performance 
>3. Reduces Overfitting
>4. Improves Visualization
<h3>DISADVANTAGES OF PCA:</h3>  
>1. Independent variables become less interpretable
>2. Data standardization is must before PCA 

<h1>IRIS_DATASET</H1>

![imagename](https://thegoodpython.com/assets/images/iris-species.png)



![imagename](https://miro.medium.com/max/2186/1*duZ0MeNS6vfc35XtYr88Bg.png)

**The above graph is 2D graph of principal component 1 against principal component2**

 _In this project the accuracy of the model has been calculated using 4 technique:_
 >1. Random Forest classifier.
 >2. KNeighborsClassifier.
 >3. Support Vector Machine.
 >4. Logical Regression.
 
* SUMMARY:
* The Iris Dataset contains four features (length and width of sepals and petals) of 50 samples of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). 
* These measures were used to create a linear discriminant model to classify the species. The dataset is often used in data mining, classification and clustering examples and to test algorithms. The relationship between pairs of features of a iris-setosa is distinctly different from those of the other two species. There is some overlap in the pairwise relationships of the other two species, iris-versicolor and iris-virginica.
* We have even plotted the Heatmap plots rectangular data as a color-encoded matrix.
* I have also showed the counts of observations present in each categorical bin using bars i.e., petal length,petal width,sepal length and sepal width.
* I have used the 'seaborn-whitegrid' style to produce a histogram which helps us to learn how three different flower classes i.e.,'Iris-setosa', 'Iris-versicolor', 'Iris-virginica' are distributed along four different features i.e.,'sepal_length ', 'sepal_width 'petal_length 'and 'petal_width'.
* In PCA, essentially we diagonalize the covariance matrix  by eigenvalue decomposition since the covariance matrix is symmetric where 𝐕 is a matrix of eigenvectors (each column is an eigenvector) and 𝐋 is a diagonal matrix with eigenvalues 𝜆𝑖 in the decreasing order on the diagonal.
* Eigenvectors of a symmetric matrix, covariance matrix here, are real and orthogonal. The eigenvectors are called principal axes or principal directions of the data. Projections of the data on the principal axes are called principal components.
* The eigen vectors with the lowest eigen values holds least information regarding the distribution of the data. On ranking the eigen values from highest to lowest in order to choose the top k eigen vectors.
* I calculated explained variance from the eigen values. The explained variance tells us how much of variance can be attributed to each of the principal components.
* In conclusion , I got the cccuracy of our model using Random Forest Classifier is equal to: 100.0 % , using KNN technique is equal to:96.67% , using SVM is equal to: 100.0% and using logical regression is equal to:100.0%.
* Therefore, the accuracy of the model depends on the technique that we are using.

THANK YOU
* Assignment during Online Internship with DLithe(www.dlithe.com)

