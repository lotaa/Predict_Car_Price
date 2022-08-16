# Car Price Prediction(End to End data Science Project)


### Definition
implement end to end data science pipeline to predict the price of old cars based on the given features.

### Dataset
      https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

### Tools I Used
* Python
* numpy
* pandas 
* Sklearn 

###  Objectives

* Loading the data
* Preprocessing the data
* Explore features or charecteristics to predict price of car
* Develop prediction models
    * linear Regression  Model
    * Multiple Regression Model
    * polynomial Regression model
* Evaluate and refine prediction model


### Decision Making




<p>When comparing models, <b>the model with the smallest MSE value is a better fit</b> for the data.</p>

<h4>Let's take a look at the values for the different models.</h4>
<p>Simple Linear Regression: Using Max Power as a Predictor Variable of Price.
<ul>
    <li>R-squared: 0.5414896258926741</li>
    <li>MSE: 292598853724.4558</li>
</ul>
</p>
    
<p>Multiple Linear Regression: Using 'year', 'max_power_bnb', 'engine_CC' and 'transmission_Manual' as Predictor Variables of Price.
<ul>
    <li>R-squared: 0.6484636261684696 </li>
    <li>MSE: 226614759251.57318</li>
</ul>
</p>
    
<p>Polynomial Fit: Using Max Power as a Predictor Variable of Price.
<ul>
    <li>R-squared: 0.6329551972845806</li>
    <li>MSE: 238566119098.2901</li>
</ul>
</p>


# Conclusion 

Comparing these three models, we conclude that the Polynomial model is the best model to be able to predict price from our dataset. This result makes sense, since we have 27 variables in total, and we know that more than one of those variables are potential predictors of the final car price.
