Distance based classifier:

The distance-based algorithm classifies the data set based on the distance between the two data points. Standard distance-based classifiers are euclidean distance, city block distance, cosine distance, chessboard, etc.




Library imported: Numpy, pandas, matplotlib, random, statistics.

Explaination

The array was created for the three classes setosa, virginica, and Versicolor. Training of the dataset was made randomly initially. The training percent was 60, and testing was 40. as each class contains 50 attributes, training
was taken as 30 %, and the rest 20% for testing after the training centroid was calculated for the training dataset. Before testing, two lists were created as list one and list two, and diff was called to calculate the nth discrete difference along the given axis. Testing was made using diff of an array created earlier and training data.

Individually all the distance method were called, and error, absolute error, mean square error, and error distance was calculated. In the end, a graph was a plot between the classifier and misclassified.

Euclidean distance: It represents the shortest distance between two point
Manhattan Distance: It is used to find the sum of absolute differences between points across all the dimensions.
Mahalanobis Distance: First, we have to find the covariance matrix, and when the covariance distance is an identity matrix, then Mahalanobis is the same as the euclidean distance
Correlation Distance: Gives the correlation coefficient distance between vectors given.
Cosine distance: Gives the angular cosine distance between vectors given.