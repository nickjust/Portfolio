## Research Paper - Recognizing Phases in Batch Production via Interactive Feature Extraction (in progress)

### Paper overview

* Feature extraction and pattern recognition in multivariate time series data (industrial processes) for identifying different manufacturing procedures with unsupervised learning and human interaction
* Developed a Multilevel Clustering Algorithm applying K-Means and K-Medoids as well as self-supervised LSTM-Autoencoder for dimensionality reduction and implemented it in Python using the libraries scikit-learn, Tensorflow, tslearn and scikit-learn-extra. 
* Enabled visual inspection and user interaction through a self-developed Guide User Interface, which facilitates the user to interactively select areas of interest based on the extracted shape features and incorporate domain knowledge with less effort.
* Evaluations of the algorithm with statistical metrics showed, that phases were successfully identified (margin of only 2 to 3 time points) based on the extracted patterns with minor human interaction.

## [Natural Language Processing Project - Automatic Speech Recognition of command words with CNN and RNN-LSTM](https://nickjust.github.io/ASR_command_words/)


### Project overview

* Realized a Automatic Speech Recognition system (ASR/NLP) to classificate command words with custom modeled CNN and RNN-LSTM
* Implementation in Python using the libraries Tensorflow, Keras and Librosa 
* Quantitative comparison and evaluation of both neural networks by 3-fold speaker independent cross validation, average evaluation metric scores (Precision, Recall, F1-Score, Accuracy)  confusion matrix and statistical t-Test analysis
* Achieved a classification accuracy of over 85% on average for both models

<p align="center">
  <img src="images/comparison_boxplot.PNG" width=450>
</p>

You can access to it **[HERE](https://nickjust.github.io/ASR_command_words/)**


## [Computer Vision Project - R-CNN for object detection and motion tracking](https://nickjust.github.io/RCNN_object_detection/)

### Project overview 
* Applied detection and classification of moving objects (Computer Vision) using self-developed Deep Neural Networks (CNN, R-CNN)
* Self-generated and manually labeled dataset of the individual object to be identified 
* Implementation in Python using Tensorflow, Keras and OpenCV 
* Extension of the algorithm to recognise the object (remote controlled car) both in individual pictures and videos in order to track its movement

<p align="center">
  <img src="images/Detection_picture.png">
</p>

You can access to it **[HERE](https://nickjust.github.io/RCNN_object_detection/)**



