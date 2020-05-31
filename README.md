# MNIST
A beginner's guide to image classification.

<b> Modified National Institute of Standards and Technology(MNIST) </b> database of handwritten digits is a cult classic among beginners and due to good reason. It is large enough for training deep neural networks and yet small enough to be managable. It is rather straight forward concept, recognize handwritten digits.

For more information about the dataset:http://yann.lecun.com/exdb/mnist/

Let's have a quick overview of the data- <br>

<img src='https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png'>


If we break down the problem, we notice that it is not some complex machine learning based image recognition problem, instead it is just an image classification problem. We have 10 classes i.e 0 to 9 where every class is for every digit. 
<h2> In this Project: </h2>
Machine Learning provides several algorithms for providing this kind of classification. I have tried to use dome of the more popular and beginner friendly algorithm: KNN, SVM and CNN.


<h3> <a url= 'https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html'>KNN</a> </h3>
k-nearest neighbors algorithm (k-NN) is a non-parametric method used for classification and regression. 
Suppose there are two categories, blue squares and red triangles, and we have a new data point i.e the green circle. Now the question arises is that this data point will lie in which of these categories. To solve this type of problem, we need a K-NN algorithm. With the help of K-NN, we can easily identify the category or class of a particular dataset.

<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/KnnClassification.svg/440px-KnnClassification.svg.png'>

As we can see that the green circle has 2 red triangles close and only one blue square, it is a red triangle

<h3><a url='https://scikit-learn.org/stable/modules/svm.html'> SVM</a></h3>
SVM is a supervised machine learning algorithm which can be used for classification or regression problems. <br>It uses complex transformations of the data to figure out complex relations between the data. 

<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Svm_separating_hyperplanes_%28SVG%29.svg/440px-Svm_separating_hyperplanes_%28SVG%29.svg.png'>

H1 does not separate the classes. H2 does, but only with a small margin. H3 separates them with the maximal margin.

Support Vector Machine is primarily used for Classification problems in Machine Learning. <br>The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.
<h3> CNN</h3>

Neural Networks are a set of algorithms, modelled loosely after the human brain, that is designed to recognize patterns.<br>

<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Typical_cnn.png/790px-Typical_cnn.png'>



A Convolutional Neural Network (CNN) is a class of deep neural networks for analysing visual imagery. It is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. 

<a url='https://www.tensorflow.org/tutorials/images/cnn'> Tensorflow</a>

TensorFlow is Google Brain's second-generation system. It is used for machine learning applications such as neural networks.

<a url ='https://www.tensorflow.org/guide/keras'>tf.keras</a> is TensorFlow's high-level API for building and training deep learning models.

<h2>What was the best?</h2>
After validating the accuracy of all the three above, I concluded that CNN provided the best result. So CNN was used to make the predictions on the test.csv data.

This Project was in colebaration with https://github.com/Rakshana0802
