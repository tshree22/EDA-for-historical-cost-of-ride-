Problem Statement
Problem Statement In the highly competitive and rapidly evolving ride-sharing industry, dynamic pricing models play a pivotal role in determining the cost of rides. A ride-sharing company might calculate the cost of a ride using a formula that considers the base fare, distance, time, and dynamic pricing factors such as demand and supply. Accurate pricing not only ensures optimal revenue generation for the service provider but also maintains customer satisfaction and loyalty. To enhance the precision of these pricing models, it is essential to identify and select the most influential factors that contribute to the historical cost of rides.

We are tasked with conducting an Exploratory Data Analysis (EDA) and predicting the variable 'Historical_Cost_of_Ride' on a dataset comprising 1,000 records related to ride-sharing service costs. The dataset includes several key attributes that could potentially influence the pricing model:

Number_of_Riders: The number of riders participating in the ride.

Number_of_Drivers: The number of drivers available at the time of booking.

Location_Category: The category of the location (Urban, Suburban, Rural).

Customer_Loyalty_Status: The loyalty status of the customer (e.g., Silver, Regular).

Number_of_Past_Rides: The number of past rides the customer has taken.

Average_Ratings: The average ratings given to the drivers by the customer.

Time_of_Booking: The time of the day when the booking was made.

Vehicle_Type: The type of vehicle booked for the ride.

Expected_Ride_Duration: The expected duration of the ride in minutes.

Historical_Cost_of_Ride: The cost of the ride, which serves as the target variable for predictive modeling.

Our objective is to perform a thorough EDA to uncover patterns, correlations, and insights within the dataset. By analyzing these attributes, we aim to identify the most significant features that influence the historical cost of a ride. This process will involve statistical analysis, data visualization, and feature selection techniques to ensure that the most relevant variables are used in constructing an effective predictive pricing model.

Ultimately, the findings from this EDA will provide a robust foundation for developing a dynamic pricing model that can accurately predict ride costs, thereby enhancing the efficiency and competitiveness of the ride-sharing service.

Hypothesis
More number of riders / high demand - There will be high amount of variability in cost and pricing as demand plays a crucial role
Location: In Urban areas , historical cost of ride will be higher as compared to suburban and rural.
Number of drivers : Driver availability can influence dynamic pricing models.
Customer loyalty status and no. of past riders would not affect the cost of ride direclty but Loyal customers might receive discounts or have access to special pricing.
The average ratings given to the drivers by the customer will not affect the cost of ride directly
Time_of_Booking: Time of day can affect demand and pricing (e.g., rush hours - high cost vs. off-peak hours- low cost).
Vehicle_Type: Different vehicle types (e.g., Sedan, SUV, Hatchback) have different pricing structures.eg premiun car will be costlier than regular ones.
Expected_Ride_Duration: Longer rides typically cost more due to increased distance and time
