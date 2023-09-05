# Brain_Tumor_Detection_Classification

Hii Readers, In this post we are going to learn about brain tumor detection using sklearn and python.

Requirements:
python (https://www.python.org/downloads/)
sklearn (pip install sklearn)
openCV (pip install opencv-python)
numpy (pip install numpy)
matplotlib (pip install matplotlib)
DOWNLOAD CODE :
Download the code from github
Download all above mentioned dependencies.
Open downloaded folder inside jupyter notebook.
Now cells as per your requirements.
STEP 1: Load Dependencies

STEP 2: Load and prepare data
Note: You can find dataset directory inside github repository link (given below) or download dataset from kaggle



STEP 3: Data Analysis


STEP 4: Data Visualization


STEP 5: Split Data
In this step, we are going to split data in two parts (training and testing), so that we can train our model on training dataset and test its accuracy on unseen (test) data.



STEP 6: Feature Scaling
In this step, we are going to use minmax scaling technique to bring all the feature values to less than or equal to 1. In order to do so, we have divided the training data by its maximum value.


STEP 7: Model Training
As we have done with preprocessing part, it is time to train our model. I am going to train model using SVM (Support Vector Machine) and Logistic Regression algorithms and then we will compare the performance of these two different models.



STEP 8: Evaluation
In this part, we will compare the scores of above two models.



As we can observe, SVM showed a great balance among training an testing score as compared to Logistic Regression. So we can reach to the conclusion that it is ideal model for this particular dataset

STEP 9: Prediction
In this step we are going to predict test dataset. Afterwards, I have checked the total number of misclassified samples out of total test samples.



STEP 10: TESTING (On test dataset)
Finally, it is the time to examine the results.



OUTPUT


So, this is all about creating a predictive model using sklearn on brain tumor dataset. Thanks for reading!
