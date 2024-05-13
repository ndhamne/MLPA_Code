The code repo contains 2 files -

preprocess.ipynb : This file preprocesses the data with following steps -

(1) Remove the time column and start reading data form the row where it begins.

(2) Create 9-feature summary files for each condition (normal, inner race fault and outer race fault).

(3) Combine the summary files into one single file and shuffle the data. 

models.ipynb : 

(1) Plot data for each condition (all data i.e. 120k points)

(2) Plot data for each condition (10 periods i.e. 2400 points)

(3) Logistic Regression model

(4) Random Forest model




Folder structure: 

- ProcessedData
|
| -- Normal
|
| -- Innerrace
|
| -- Outerrace
|
| -- stats
