<h1> Voice-Classification </h1>

<h3>1. This database was created to identify a voice as male or female </h3>
    
<h3>2. Packages Used to solve this classification problem </h3>

          a. import pandas as pd
          b. import numpy as np
          c. import matplotlib.pyplot as plt
          d. import seaborn as sns
          e. from sklearn.preprocessing import LabelEncoder
          f. from sklearn.preprocessing import StandardScaler
          g. from sklearn.model_selection import train_test_split
          h. from sklearn.svm import SVC
          i. from sklearn import metrics
          j. from sklearn.metrics import classification_report,confusion_matrix
          k. from sklearn.metrics import roc_curve

<h3>3. Load the dataset   </h3>   
<h3>4. Understand and prepare the data </h3>
<h3>5. Checking for missing values. </h3>
    
        a. 0 Null-values present in the dataset.
  
<h3>5. Get Shape and Distribution. </h3>

        a. Shape of Dataset --->  (3168, 21)

<h3>5. Get Shape and Distribution. </h3>
<h3>5. Split your data into a training set and a testing set. </h3>
<h3>5.Model Evaluation. </h3>
<h3>5.Confusion Matrix. </h3>

![Alt Text](https://github.com/Aamir8539/SVM-Voice-Classification-/blob/main/download.png)

<h3>5.Classification report. </h3>

                        precision    recall  f1-score   support

                   0       0.99      0.97      0.98       493
                   1       0.97      0.98      0.98       458

            accuracy                           0.98       951
           macro avg       0.98      0.98      0.98       951
        weighted avg       0.98      0.98      0.98       951

<h3>5.ROC Curve. </h3>

![Alt Text](https://github.com/Aamir8539/SVM-Voice-Classification-/blob/main/ROC.png)
