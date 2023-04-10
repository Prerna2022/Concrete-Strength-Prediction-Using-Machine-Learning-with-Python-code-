# Concrete-Strength-Prediction-Using-Machine-Learning-with-Python-code-
This study aims to determine the influence of the content of water and cement, water–binder ratio, and the replacement of fly ash and silica fume on the durability of high performance concrete. Strength of concrete will be predicted using various regression method and performance of the models will be analyzed using different performance metric
# we are going to analyze the Concrete Compressive Strength dataset and build a Machine Learning model to predict the quality:
Dataset
Dataset knowledge
Importing modules
Reading data
Study dataset
Handling null values
Exploratory data analysis
Dividing independent and dependent variables
Splitting the data
Feature scaling
Applying model
Predicted values vs original values
Saving the model
 

Dataset
We will use a concrete compressive strength dataset which was retrieved from the Kaggle, you can click here for the dataset.

Dataset knowledge
If you download this dataset, you see that several features affect the quality of concrete. So we discuss brief of each feature:

cement: a substance used for construction that hardens to other materials to bind them together.

slag: Mixture of metal oxides and silicon dioxide.

Flyash: coal combustion product that is composed of the particulates that are driven out of coal-fired boilers together with the flue gases.

Water: It is used to form a thick paste.

Superplasticizer:  used in making high-strength concrete.

Coaseseaggregate: prices of rocks obtain from ground deposits. 

fineaggregate: the size of aggregate small than 4.75mm.

age: Rate of gain of strength is faster to start with and the rate gets reduced with age.

csMPa: Measurement unit of concrete strength.

Now, we will import some important modules:

Importing Modules
For further process we have to import some important modules present in python:

# importing pandas
import pandas as pd
#importing numpy
import numpy as np
#importing matplotlib
import matplotlib.pyplot as plt
#importing seaborn
import seaborn as sb
So, we import pandas for data analysis, NumPy for calculating N-dimensional array, seaborn, and matplotlib to visualize the data.

Reading data
Generally, we use a dataset in the form of a CSV file, for reading this CSV file we will use the panda’s library, let’s see:

df = pd.read_csv(' Concrete_data.csv ')
