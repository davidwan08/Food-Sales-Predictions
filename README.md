# Food Sales Predictions
## Predicting Item Sales by Data Modeling and Analysis

**Project by David Wan**


### Business Problem:

- For this sales prediction project, I would like to examine the properties of products and outlets and use that information to help me determine what factors affect sale of certain items.
- With this information, I want to determine what would help improve sales of certain items and determine what factors and conditions play a role in item sales.


### Data:

![sales_predictions.csv](https://github.com/davidwan08/sales-predictions/blob/main/sales_predictions.csv)

> This is the raw csv file I used to perform my sales predictions modeling and analysis.


## Methods
- I used simple imputation methods to tackle missing values associated with the dataset.
- I then scaled numerical information using the Scaler method and encoded categorical information using the OneHotEncoder method to help fit the model needed for analysis.
- I have utilized linear regression modeling and regression tree modeling to help model sales prediction data.


## Results

#### Total Item Outlet Sales By Outlet Establishment Year

![Outlet Sales By Year](https://github.com/davidwan08/sales-predictions/blob/main/Outlet%20Establishment%20Year.png)

> This lineplot shows how the total item outlet sales vary based on outlet establishment year.

#### Distribution of Item Sales vs Visibility by Outlet Type

![Item Sales vs Visibility](https://github.com/davidwan08/sales-predictions/blob/main/Item%20Sales%20Visibility%20Scatterplot.png)

> This scatterplot shows how the item sales vary based on the visibility of the item depending upon outlet types.


## Recommendations:

- Based on the data available from the sales predictions analysis, I would recommend adjusting item visibility based on the type of outlets.
- For instance, grocery stores tend to have high visibility of items, whereas supermarkets tend to have lower visibility of items. 
- I think increasing variety of items sold at grocery stores will help improve item sales and help consumers find the food items they desire to buy by giving them more options.
- I also think that decreasing variety of items in supermarkets would also help with boosting sales of certain other items that have very minimal visibility. In exchange, perhaps promoting seasonal food items on a periodic basis would definitely help target certain consumer groups and make sales more effective during certain months/seasons.
- In addition, I would definitely try to examine sales data from 1998 to figure out what events took place that could have caused very low food sales numbers that year. Perhaps there was an overall supply shortage or goods, or perhaps there was a merger event of different corporations that could have caused this dip in food sales numbers.


## Limitations & Next Steps:

- There was quite a bit of missing information about item weights and outlet sizes. I do believe that item weights could play a role in determining how well it sells based on the item type.
- In addition, there was a lot of missing information about outlet sizes. These size details could play a role in figuring out whether increasing the outlet size would help with increased exposure of items for consumer sales or not.
- I will consult the subject matter expert and see what types of outlets are involved with the food sales information.
- I will also employ more complex imputation processes that better predict information based on categorical information and characteristics of certain features to give more accurate modeling predictions.


### For Further Information:

For any additional questions or concerns in regards to my sales predictions, please contact me at **davidwan08@gmail.com**. Thank you!
