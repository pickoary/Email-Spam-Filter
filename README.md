#Email-Spam-Filter

Programming Exercise 6 in Machine Learning course by Andrew Ng on Coursera. In this exercise one shall learn to use support vector machines (SVMs) to build a spam classifier.

The details of this assignment are described in tutorial.pdf

The codes are written in GNU Octave. For further info on Octave please see http://www.gnu.org/software/octave/

This set includes the following functions:

ex6.m - Octave script for the first half of the exercise,
ex6data1.mat - Example Dataset 1,
ex6data2.mat - Example Dataset 2,
ex6data3.mat - Example Dataset 3,
svmTrain.m - SVM training function,
svmPredict.m - SVM prediction function,
plotData.m - Plot 2D data,
visualizeBoundaryLinear.m - Plot linear boundary,
visualizeBoundary.m - Plot non-linear boundary,
linearKernel.m - Linear kernel for SVM,
gaussianKernel.m - Gaussian kernel for SVM,
dataset3Params.m - Parameters to use for Dataset 3, 
ex6_spam.m - Octave script for the second half of the exercise,
spamTrain.mat - Spam training set,
spamTest.mat - Spam test set,
emailSample1.txt - Sample email 1,
emailSample2.txt - Sample email 2,
spamSample1.txt - Sample spam 1,
spamSample2.txt - Sample spam 2,
vocab.txt - Vocabulary list,
getVocabList.m - Load vocabulary list,
porterStemmer.m - Stemming function,
readFile.m - Reads a file into a character string,
processEmail.m - Email preprocessing,
emailFeatures.m - Feature extraction from emails.
