# Gold annual average price prediction.


## Data analysis of gold commoditie price.

### Introduction.

Gold is a important element of global monetary reserve and is widely used for jewellery, investments, central bank reserves and thechology. It is useful in medicine and dentistry and, lately, has emerged as a key nanomaterial. The gold market is highly liquid. Gold held by central banks and other major institutions and as retail jewellery is reinvested in the market. 
Gold prices depends upon a complex array of factors, including Treasury yields, the money supply and strength of the dollar, so trying to pin point the most relevant variables for the predicting model is difficult, mostly because of the scarcity of the free data, when most of the years before 2000 are missing. 

### Model 1 and Model 2 

The first model isn't the right and complete one, most of the code and data used don't follow the principal assumptions which justify the use of linear regression. So the model 1 was only a test for the model 2, which is the final model, where all the assumptions are reviewed and assessed. __The rest of the "research" will only be conducted for the model 2 data and code.__

### Data

So for choosing the variables that are going o be used for the liner regression model it is useful to pick the best variables with good correlation and background to the gold prices (annual average). It was a bit difficult to get data with the same annual date for the dataset of the observations, so the observations goes from 2004 to 2020.  

The dependent variables try to emulate some of the financial market ecosystem, then to lessen the chance for a overfittin model, it was chosen only one or two variables. For the possible determinants was selected the demand, interest rates, inflation expectation and some varibles as a reflexion of the financial markets, The reason that supply is not used is because the gold annual supply seems to be constant, amounted to 4,490 tons in 2018 and is projected to amount to 4,533 tons in 2023, a really small change between years. 

1. __Demand:__ the world GDP seems to be one of the best indicators, as reflect the monetary measure of the market vaue of all the final goods and services produced in a specific time period.

2. __Interest Rates:__ the 10-year treasury is used as a interest rate variable in the model, as  it signal investor confidence and is used as proxy for many other important financial matters.

3. __Inflation Expectation:__ there are two variables that are determinants of inflation expectation, 5-year for the medium and 10-year for the long expectancies. Commodities are often portrayed as a real hedge against inflation risk so this two variables are important for the model.  

4. __Commodity Prices and Financial Variables:__ MSCI indexes are used as a reflexion of the financial markets, companies from emerging(MSCI emerging markets) and developed countries(MSCI world index).

![Image of fitted and atual observations](http://lmsotfy.com/fitted_vs_actual_observations.png)
