# hello-world
My first repository
Então,estou entrando para esse mundo sensacional de dados e vou ser uma pessoa reconhecida! 


import matplotlib.pyplot as plt
from sklearn import metrics
from sklearn.model_selection import train_test_split
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
from sklearn.metrics import accuracy_score, precision_score, recall_score,confusion_matrix, precision_recall_curve
import pandas_profiling

test = pd.read_csv(r"C:\Users\micael.custodio\OneDrive\OneDrive - JSL SA\DHDSC\DESAFIO TITANIC\test.csv")
train = pd.read_csv(r"C:\Users\micael.custodio\OneDrive\OneDrive - JSL SA\DHDSC\DESAFIO TITANIC\train.csv")

#Retirndo colunas que parecem ser irrelevantes no momento
train = train.drop(columns=['PassengerId','Ticket','Name','Embarked','Cabin'])
train.head()

#Retirndo colunas que parecem ser irrelevantes no momento
test = test.drop(columns=['Name','Cabin','Embarked'])

#Inseri a média de idade nos campos que estavam vazios
train['Age'].fillna(train['Age'].mean(), inplace=True)
test['Age'].fillna(test['Age'].mean(), inplace=True)

asasasasasasas

asasas

asasasas
scacacascacasc
