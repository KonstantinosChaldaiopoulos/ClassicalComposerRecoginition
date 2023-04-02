# Recognizing classical composers in untrained data

This project performs music genre classification using machine learning techniques. The steps involved in this project are:

1) Feature extraction from audio files using pyAudioAnalysis library.
2) Normalization of extracted features.
3) Creating a pandas dataframe from the normalized features and exporting it to a CSV file.
4) Merging the produced dataframes and adding labels to them.
5) Selecting the top N features using a classifier of your choice.
6) Training a classifier using one of several options (SVM, Logistic Regression, Random Forest, KNN, Neural Network, or Naive Bayes) on the selected features.
7) Performing 10-fold shuffle split cross-validation on the training data to evaluate the performance of the classifier.
8) Testing the model with new data and calculating accuracy and F1 score.

An example of the outputs can be found here:
https://nbviewer.org/github/KonstantinosChaldaiopoulos/ClassicalComposerRecoginition/blob/main/Demo.ipynb

## Prerequisites
1) Python 3.8 or higher
2) pandas, numpy, pyAudioAnalysis, scikit-learn, scipy

## Steps to Run the Code
1) Clone the repository.
2) Run the code in Jupyter Notebook or Google Colab.
3) Ensure that the audio files are in the specified directory.
4) Create the audio files by changing the file paths and file names as required in the code. Run the first script multiple time in order to generate the files.
5) Check the output for the F1 score and accuracy of the model.

## Notes 
A powerpoint presentation that includes confusion matrices of the results is available.

## Authors
This code was created by Konstantinos Chaldaiopoulos

