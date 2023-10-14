# SimpleDNN

This is a single dense layered DNN that is trained with a sample dataset that has a relationship defined within it as below.

  If X is 2, then Y is 5
  If X is 4, then Y is 9 & so on

If you notice carefully Y is always 2 times X value plus 1. So we can define Y as 2X + 1

Let us train the model with the below sample inputs for X and outputs for Y and verify if the  model is able to understand the business rule within it and make predictions for new set of data later.

x = [1.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0, 9.0]
y = [3.0, 5.0, 7.0, 9.0, 11.0, 13.0, 15.0, 17.0, 19.0]

Pls feel free to download the code and play with defining new sample datasets for X and Y with different business rules and train the model to identify this and make predictions rightly.
