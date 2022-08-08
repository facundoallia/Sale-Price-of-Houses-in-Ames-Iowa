# Sale-Price-of-Houses-in-Ames-Iowa
A regression model predicting house prices using neural networks

## About the project

The project was carried out as part of the data science bootcamp at Henry.

The goal of the project is to create a house price prediction model for Ames, Iowa. To achieve the goal, a neural network regression-type model is developed using Keras and Scikit-Learn.

## About data processing

In the first instance, an exploratory analysis of the data was carried out, finding 80 features apart from the market price. Missing data was treated as well as outliers.

![Image text](https://github.com/facundoallia/Sale-Price-of-Houses-in-Ames-Iowa/blob/main/Assets/dat.jpg)

A coding of the categorical variables was carried out, emphasizing the variable "Neighborhood". In addition, dummy variables were used to indicate the absence or presence of any categorical effect.

![Image text](https://github.com/facundoallia/Sale-Price-of-Houses-in-Ames-Iowa/blob/main/Assets/nb.png)

## About the model

A neural network model was created with Keras. It consists of 4 layers each with 50 neurons. Adam optimization was used. Adam optimization is a stochastic gradient descent method that is based on adaptive estimation of first-order and second-order moments.

After 1000 epochs the model was trained obtaining the following metrics:

![Image text](https://github.com/facundoallia/Sale-Price-of-Houses-in-Ames-Iowa/blob/main/Assets/md.png)

+ MAE: 3324.110065887578
+ MSE: 118403266.08580635
+RMSE: 10881.32648558099
+ VarScore: 0.9817379379839103
+ RMSLE: 0.049078200765782204

![Image text](https://github.com/facundoallia/Sale-Price-of-Houses-in-Ames-Iowa/blob/main/Assets/rg.png)

The residuals are presented with the following distribution:

![Image text](https://github.com/facundoallia/Sale-Price-of-Houses-in-Ames-Iowa/blob/main/Assets/res.png)
