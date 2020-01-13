# FINGERPRINT-CLASSIFICATION-USING-SVM
Built a multi-class classifier from the non-linear support vector machines (RBF kernel) using the dataset having fingerprint images. SVM library function in Python was used. A checker program was used that takes fingerprint images as input to train the model. It then predicts the identification number of the person. The checker program resulted in a performance gain of 82%. 

Downloaded the training dataset of 126 fingerprints of 21 persons (6 thumb fingerprints per person)
from this link http://bit.ly/2phOMcN. The file names follow x y.bmp convention, where x is the
identification number of a person, while y is a serial number of fingerprint snap for that person. All
images are in BMP format, and resolution is 256 × 256.

I have built a multi-class classifier from the non-linear support vector machines (RBF kernel) using the
training set features you extracted in the previous step. I used the support vector library
function in your preferred programming language.

Since SVM is a binary classifier, in order to make it do multi-class (i.e., 21 classes in this assignment) prediction, I used the one-vs-all strategy. Wrote a checker program that takes a fingerprint image as input, and based on the model you trained
in the previous step prints the identification number of the person that you will get by prediction.

You can use the checker program to see the test A performance. I have tuned various parameters of RBF kernel
based SVM to get a better decision boundary. I recommend you do the parameter tuning. The testA
dataset contains 21 fingerprint images. Download link for this testA dataset is http://bit.ly/2IrM1yw
