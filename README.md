# diabettis


The aim of this project is to explore the Pima Indian dataset of women with and without diabetes. 

  1. Descriptive Analytics: examining the composition of my dataset.
  2. Predictive Analytics: unsupervised and supervised techniques.

I first reduced the features using an unsupervised machine learning algorithm called Principal Component Analysis, PCA. Then, becasue I had far more cases in the negative class (no diabetes) than the positive class (diabetes), I used an oversampling technique on my training dataset in order to balance out the classes. I used 4 supervised algorithms using the PCA-reduced and balanced datset: k-Nearest Neighbors, Support Vector Machine (SVM), Decision Tree Classification, and Gaussian Naive Bayes. 

Then, I used another unsupervised technique called k-means clustering to plot 2 features. 
