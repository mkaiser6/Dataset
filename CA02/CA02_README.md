***CA02 Assignment - Spam Email Detection using Naive Bayes -- Max Kaiser***


**Assignment Description:**

*Step 1:* Training the model with set of emails labelled as either from Spam or Not Spam. There are 702 emails equally divided into spam and non spam category. 

*Step 2:*  Test the model on 260 emails. Model will try to predict the category of the emails and compare the accuracy with correct classification that we already know

Assumptions: independence in features 

2 Files: 

train-mails (442 text files)
test-mails (260 text files)


______________________________________________________________________________________________________________________

**Packages to import:**

#import os

#import numpy as np

#from collections import Counter

#from sklearn.naive_bayes import GaussianNB

#from sklearn.metrics import accuracy_score


______________________________________________________________________________________________________________________


**Installation Instructions**

Please find two zip files titled 'test-mail.zip' and 'train-mail.zip' in the CA02 foler to download 

Download & save the data and use the path when reading/accesing it 

When using Jupyter Notebook please adjust your file path (username and folder) on your local Computer: 

TRAIN_DIR = '/Users/maxkaiser/Desktop/train-mails' 

TEST_DIR = '/Users/maxkaiser/Desktop/test-mails'

*or* 

Please use the following code to share files/ mount your Google Drive in Colab 

from google.colab import drive 
drive.mount('/content/drive',force_remount=True

This will allow access to the drive when you enter the authentication code.  

______________________________________________________________________________________________________________________

Please feel free to reach out if you have any questions or issues with accessing or understanding any documents 

Contact me via email at mkaiser6@lion.lmu.edu or via Teams :) 
