# Abalone_Dataset


 given a data file abalone.csv. Abalones are marine snails. The dataset has been prepared
with the aim of making age predictions easier. Customarily, the age of abalone is determined by
cutting the shell through the cone, staining it, and counting the number of rings through a microscope.
But it is a tedious and time-consuming task. Therefore, other measurements, which are easier to
obtain, are used to predict age.

Attribute information:
Given is the attribute name, attribute type, the measurement unit, and a brief description. The number
of rings is the value to predict: either as a continuous value or as a classification problem.

Name / Data Type / Measurement Unit / Description
* Length / continuous / mm / Longest shell measurement
* Diameter / continuous / mm / Diameter of the shell calculated as perpendicular to length
* Height / continuous / mm / Height of the shell with meat in shell
* Whole weight / continuous / grams / Weight of whole abalone
* Shucked weight / continuous / grams / Weight of meat
* Viscera weight / continuous / grams / Gut-weight (after bleeding)
* Shell weight / continuous / grams / Weight of the shell after being dried
* Rings / integer / -- / Number of rings in a shell. (Adding 1.5 to the number of rings gives the
age of abalone in years)

The code:

* Loads the dataset into the Spyder Enviornment.
* Applys Linear Regression between the traget attribute and the attribute wihich has the highest pearson cofficient with the target attribute(Fitting a Straight line Between two attributes).
* Applys Linear Regression between the target attribute and all the other attributes(Fitting a straight line in higher Dimensions.)
* Applys Polynomial Regression between the target attribute and the attribute which has the highest pearson cofficient with the target attribute(Fitting a polynomial curve between two attibutes).
* Applys a Polynomial Regression between the target attribute and all the other attributes(Fitting a polynomial curve in the higher dimension).


