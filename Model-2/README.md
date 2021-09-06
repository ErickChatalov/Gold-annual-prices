# Data analysis and Gold annual average price prediction.

  
<div>
    <div>
        <p>It is easier to make a model for prediction using the average gold prices from all months, than to choose a month for a closing price,as the independent variables don't need to be correlated by date. So all the data that was a monthly observation needed to be transformed into a annual average.
        </p>
        <p style="margin: 5px">The variables were aggregated into the dataset below:</p>
        <img src="./images/image2.jpg">
    </div>
</div>

## Dependent and Independent Variables.

<p>The dependent variable of this model was created around the Gold annual average price adjusted for inflation in dollars, as you can see in the graph below the price have a positive trend with a correction in 2015 and an increase in the following years.
</p>
<img src="./images/image10.jpg" style="margin: auto;display: block;">
<p>So we can use all the variables in the model, it is necessary a linear relation between the dependent variable and all the independent variables and for outliers.
</p>
<img src="./images/image3.jpg" style="margin: auto;display: block;">
<img src="./images/image5.jpg" style="margin: auto;display: block;">
<img src="./images/image4.JPG" style="margin: auto;display: block;">
<p>When we test for linearity, using the multiple scatterplot, it is possible to see a linearity with almost all variables, but the MSCI's variables do not seem  to have as clear of a linearity compared with the others. The MSCI_EM variable is a more realiable for the the variance of the gold average prices than the MSCI_WN, at least in this time frame of 2004-2020. The rest of the variables seems to have a high correlation with the dependent variable.
</p>

## Model Fits and Regression Analysis.





