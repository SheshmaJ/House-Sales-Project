# House-Sales-Project
Predictive Modeling and Exploratory Analysis of Housing Sales Data
House sales for a county in Washington state.

Objective:

• Predict house prices using key features (e.g., square footage, location, amenities).

• Identify trends and factors influencing housing prices.

Tools Used:

• Python (Pandas, Matplotlib, Seaborn, Scikit-learn).

• Statistical analysis, data cleaning, and machine learning .

Workflow Overview

Data Import & Exploration: Loaded dataset with 21,613 records and 21 features.

Examined data types, missing values, and initial statistics.

Data Cleaning and Preprocessing

Handled missing values

Fixed outliers

Converted date column to datetime format.

Feature Engineering:Created new feature-per_squarefoot_price,Age_house,Total living area

Discretized variables:price into bins,Grade and condition into bins.

Redundant Columns:Dropped IDs and derived features (e.g., sqft_living15).

Exploratory Data Analysis (EDA)

Analyzed correlations, centrality, distributions, and trends.

Visualized price drivers (e.g., waterfront, grade, location).

Modelling

Trained Supervised learning model to predict prices.

Evaluated performance using MAE, RMSE, and R².

Conclusion/Key findings:
Given the data set "house_sales", we cleaned, performed EDA, and trained & evaluated machine learning models. We found a notable variables that influence price.The highest predictors of price are size, grade, location, amenities of the location. One notable finding is that listings during the spring/summer tend to sell at higher prices.


Recommendations
For prospetive buyers looking for a discount to homes, size will play an important factor when evaluating a properties worth.

Grade played an important role for price as well, remodelers or discount shoppers should take note of grades.

Amenities such as waterfront and view can prove to be huge discount for people looking for homes that don't need such things.

Location of the porperty played an big role in price. Expensive houses clustered together geographically. This suggests a possible unknown variable that could be influencing prices. Buyers looking for discounts should avoid certain locations. Further exploration is also recommended.

Listings during summer and spring tended to command higher premiums. Possible factors influencing this could be a whole host of things. Further exploration is recommended.

Age affected the price moderately in a negative manner. With a correlation coefficient of -.54, age's effects on price were moderate. Buyers looking for opportunities can also consider age as an important factor.




Special Thanks to my team mate Caly Nyugen
