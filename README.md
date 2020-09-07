# Introduction and Business Problem
Accidents occur often and the severity of the accidents typically requires a different response from authorities and other road users. Knowing the severity of a car accident can be incredibly important in helping road users make an assessment of how to navigate the road system to avoid exacerbating the situation.  This can help road user re-route to alternate routes, and avoid congesting road ways where emergency services might need to use to provide critical aid to those hurt in an accident and likely save more lives.
The goal of this project is to develop a supervised machine learning model that would help a road user to predict car accident severity with reasonably high accuracy.


# Data being used for this project
The data used in the project will the be the "Data-collisions.csv" file provided by the capstone project. The file has  194,673 rows and 38 columns. The target column is the Severitycode which has two states. 1 for slight accident with property damage and 2 for a severe accident with resulting injury.
 
Several key columns such weather, road condition and light conditions are missing data that will need to be imputed or dropped as necessary.
 
 There are several columns that are meaningingless and will need to be dropped from the dataset such as the object column which is merely a sequence numbering of the rows. This will be dropped during data preparation for modeling. Other columns such as reportno that do not add value to the modeling will also be evaluated and possibly dropped from the modeling during data preparation stage.
 
Severitycode column is duplicated.
 
 Data is imbalanced with more data showing cases where severity is lower i.e property damage compared with data showing a higher severity of injury. modeling will need to account for this appropriate i.e potentially using downsampling techniques.

