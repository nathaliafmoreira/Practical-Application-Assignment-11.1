# Practical-Application-Assignment-11.1
Practical Application Assignment 11.1 - Berkeley

In this application, we explored a dataset with information of 3 million used cars. 
Our goal was to understand what factors make a car more or less expensive.
Findings:
- The features "size", "condition", "cylinders", "VIN", "drive", "paint_color" have many null values, so I decided didn't use them in the model.
- Non-Numeric features with many unique values were excluded from the data frame, like: "region" and "model".
- For Almost 80% of the cars the transmission is automatic.
- The fuel is gas for 84% of the cars in the dataset.
- Type Sedan and SUV is almost 50% of the cars in the dataset.
- The price is concentrade up to $100K.
- The model that brought a better result was the Decision Tree. 

According to this model, the most relevant characteristics for the price of a car are: year (converted into "age", in the analysis), kilometers (odometer), followed by type sedan and fuel diesel.
