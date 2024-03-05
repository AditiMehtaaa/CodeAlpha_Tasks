The Dataset for this task is taken fron the 'datasets' module of sklearn

The Iris data has 5 features, 
1) Data -- is in an array of the values of ['sepal length (cm)', 'sepal width (cm)', 'petal length (cm)', 'petal width (cm)']
2) target -- in the array of 0, 1, and 2 for the respective targets
3) DESCR -- description of the data
4) target_names -- class of Iris, i.e., ['setosa', 'versicolor', 'virginica']
5) feature_names -- contains the names of the features whose data is taken, ['sepal length (cm)', 'sepal width (cm)', 'petal length (cm)', 'petal width (cm)']

The data for the feaures have been taken in 'centimeters(cm)

Using pandas DataFrame module converted this array Iris data into a dataframe, that is much easier to explore and analyse. 

The famous Iris database, first used by Sir R.A. Fisher. The dataset is taken
from Fisher's paper. Note that it's the same as in R, but not as in the UCI
Machine Learning Repository, which has two wrong data points.

This is perhaps the best known database to be found in the
pattern recognition literature.  Fisher's paper is a classic in the field and
is referenced frequently to this day.  (See Duda & Hart, for example.)  The
data set contains 3 classes of 50 instances each, where each class refers to a
type of iris plant.  One class is linearly separable from the other 2; the
latter are NOT linearly separable from each other.
