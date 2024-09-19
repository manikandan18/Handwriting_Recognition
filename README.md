# Handwriting_Recognition

The handwriting recognition task is the Supervised Learning classification task where handwritten images of texts of 2 individuals are fed. The input is the .png text image of individual word with name as "Mani_1.png" or "Priya_1.png".
The output label will be classified as either "Mani" or "Priya". 

For this pre-processing, text image files with multiple sentences are cropped as individual word images. 

Then, individual word images are trained and classified with different classifiers like SVM, Convolutional Neural Networks and Transformer models. The accuracy and
percision is checked. The model fit input is word image but output is either 'Mani' or 'Priya' depending on whose handwriting it is.

1. For pre-processing step, pytesseret python library used to crop and convert to individual word images.
2. For Support Vector Machines, sklearn's svm package is used for classification.
3. For convolutional Neural Networks, Tensorflow.keras libraries are used with RelU as activation function for classification.
