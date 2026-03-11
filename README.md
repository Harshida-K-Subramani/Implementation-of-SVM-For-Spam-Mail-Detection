# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import the necessary python packages using import statements.
2. Read the given csv file using read_csv() method and print the number of contents to be displayed using df.head().
3. Split the dataset using train_test_split.
4. Calculate Y_Pred and accuracy.
5. Print all the outputs.
6. End the Program 

## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
Developed by: HARSHIDA K S
RegisterNumber: 212224040108

import chardet

file='spam.csv'

with open (file,'rb') as rawdata:

result = chardet.detect(rawdata.read(100000))
    
result

import pandas as pd

data=pd.read_csv("spam.csv",encoding='windows-1252')

data.head()

data.info()

data.isnull().sum()

x=data["v1"].values

y=data["v2"].values

from sklearn.model_selection import train_test_split

x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)

from sklearn.feature_extraction.text import CountVectorizer

cv=CountVectorizer()

x_train=cv.fit_transform(x_train)

x_test=cv.transform(x_test)

from sklearn.svm import SVC

svc=SVC()

svc.fit(x_train,y_train)

y_pred=svc.predict(x_test)

y_pred

from sklearn import metrics

accuracy=metrics.accuracy_score(y_test,y_pred)
*/
```

## Output:

## ENCODING

<img width="1121" height="45" alt="Screenshot 2026-03-11 155156" src="https://github.com/user-attachments/assets/972f5df3-cf27-4ca6-9d87-bc9d97b5d628" />

## HEAD():

<img width="970" height="276" alt="Screenshot 2026-03-11 155203" src="https://github.com/user-attachments/assets/a1235599-330c-4422-8b20-c7185339d2ac" />

## isnul().sum

<img width="419" height="189" alt="Screenshot 2026-03-11 155208" src="https://github.com/user-attachments/assets/354b77cc-9925-4dae-a932-edd1c348e590" />

## Prediction of Y

<img width="960" height="111" alt="Screenshot 2026-03-11 155215" src="https://github.com/user-attachments/assets/39372e84-3c9c-4440-bc3d-425ff9af0905" />

## Accuracy

<img width="372" height="50" alt="Screenshot 2026-03-11 155220" src="https://github.com/user-attachments/assets/977ec633-1bc7-4ca2-afaf-ab2959cf734d" />


## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
