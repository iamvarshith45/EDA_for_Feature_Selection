# EDA_for_Feature_Selection
Exploratory Data Analysis (EDA) is an approach used in data analysis that uses various techniques to maximize insight into a dataset, and uncover underlying structures, patterns and analyze relationships between variables, detect outliers and anomalies, test underlying assumptions, and most important is feature selection for training Machine Learning models.


The given dataset consists of data related to ride sharing service costs, including various factors that can influence the dynamic pricing model of rides. It consists of 1,000 records with the following key attributes (columns):

Number_of_Riders - The number of riders participating in the ride.
Number_of_Drivers - The number of drivers available at the time of booking.
Location_Category - The category of the location (Urban, Suburban, Rural).
Customer_Loyalty_Status - The loyalty status of the customer (e.g., Silver, Regular).
Number_of_Past_Rides - The number of past rides the customer has had.
Average_Ratings - The average ratings given to the drivers by the customer.
Time_of_Booking - The time of the day when the booking was made.
Vehicle_Type - The type of vehicle booked for the ride.
Expected_Ride_Duration - The expected duration of the ride in minutes.
Historical_Cost_of_Ride - The cost of the ride, which serves as the target variable for predictive modeling.



Univariate Analysis is the statistical examination of one variable at a time.
It helps in understanding the distribution, central tendency, dispersion, and patterns of a single feature.
This is the first step in EDA, allowing us to analyze individual attributes before exploring relationships between multiple variables.
detects Outliers & Anomalies
identifies Data Distribution (Normal, Skewed, etc)
helps in Feature Engineering
helps in Data Cleaning (Handling missing values)


Bivariate analysis is a statistical technique that examines the relationship between two variables. It helps in understanding how one variable changes in relation to another and it is a crucial step in Exploratory Data Analysis in order to identify trends, dependencies, and patterns in data.
the target variable is Historical_Cost_of_Ride, so we find correlation between target variable (Historical_Cost_of_Ride) and other features.
This analysis will help us identify which features are most important and guiding our feature selection process for predictive modelling.
