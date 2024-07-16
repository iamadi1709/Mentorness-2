# Mentorness-2
In this project, We have developed a machine learning model to predict the risk of a heart attack based on various medical and demographic factors. Early prediction can significantly improve patient outcomes by enabling timely medical intervention and lifestyle changes.

**Predicting Restaurant Ratings**
**Project Overview**
This project aims to develop a machine learning model to predict the aggregate rating of a restaurant based on various features related to the restaurant's characteristics and operations. Accurate predictions of restaurant ratings can help restaurant owners and customers make informed decisions.

**Table of Contents**
**Introduction**
**Dataset Description**
**Exploratory Data Analysis (EDA)
Data Visualization
Modeling
Model Evaluation
Results and Discussion
Conclusion
Future Work**

How to Use
Dependencies

**Introduction**
Restaurant ratings play a crucial role in influencing customer choices. Predicting these ratings accurately can provide valuable insights to restaurant owners to improve their services and attract more customers. This project involves the development of machine learning models to predict restaurant ratings based on various features.

**Dataset Description**
The dataset contains information about restaurants, including:

Restaurant ID: Unique identifier for each restaurant.
Restaurant Name: Name of the restaurant.
Country Code: Numeric code representing the country where the restaurant is located.
City: Name of the city where the restaurant is situated.
Address: Physical address of the restaurant.
Locality: Neighborhood where the restaurant is located.
Locality Verbose: Detailed description of the locality.
Longitude: Geographical longitude of the restaurant's location.
Latitude: Geographical latitude of the restaurant's location.
Cuisines: Types of cuisines offered by the restaurant.
Average Cost for Two: Average cost for a meal for two people.
Currency: Currency used for transactions in the restaurant.
Has Table Booking: Indicator of whether the restaurant accepts table bookings.
Has Online Delivery: Indicator of whether the restaurant offers online delivery.
Is Delivering Now: Indicator of whether the restaurant is currently delivering.
Switch to Order Menu: Indicator of whether the restaurant has switched to an order menu.
Price Range: Price range category of the restaurant.
Aggregate Rating: Overall rating of the restaurant.
Rating Color: Color code representing the rating.
Rating Text: Text description of the rating.
Votes: Number of votes received by the restaurant.

**Exploratory Data Analysis (EDA)**
Initial exploration of the dataset was performed to understand data distribution, identify missing values, and detect outliers. Key analyses included:

**Location Analysis:** Distribution of restaurants across different cities and countries.
**Cuisine Analysis:** Popularity and variety of cuisines offered.
**Cost and Rating Analysis:** Distribution of average cost for two people and aggregate ratings.
**Data Visualization**
Visualizations were created to understand relationships between variables:

Heatmap: Showing correlations between various features.
Bar Charts: For categorical variables like cuisines, price range, and booking options.
Scatter Plots: To visualize the relationship between cost and ratings.
Modeling
Four machine learning models were selected for prediction:

**Linear Regression**
**Decision Tree**
**Random Forest**
**Gradient Boosting**
Each model was trained using the following steps:

Data preprocessing
Splitting data into training and test sets
Hyperparameter tuning
Model Evaluation
The models were evaluated using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²) score. Here are the results:

Linear Regression
MSE: 1.50
MAE: 0.87
R²: 0.3407
Decision Tree
MSE: 0.10
MAE: 0.20
R²: 0.9579
Random Forest
MSE: 0.09
MAE: 0.19
R²: 0.9608
Gradient Boosting
MSE: 0.10
MAE: 0.21
R²: 0.9579
Results and Discussion
Best Performing Model: Random Forest, with the lowest MSE and highest R² score, indicating excellent predictive performance.
Key Insights: Features such as cuisines, average cost for two, and location are significant predictors of restaurant ratings.
Model Limitations: Potential data quality issues and model assumptions.
Conclusion
The predictive models developed in this project show promise in estimating restaurant ratings accurately. The Random Forest model, in particular, demonstrated excellent performance, making it a valuable tool for restaurant owners and customers.

**Future Work**
Future improvements could include:

1. Incorporating additional data sources for more features.
2. Exploring other advanced machine learning algorithms.
3. Applying the model to real-time rating prediction and monitoring.
   
**How to Use**

1. Clone the repository: git clone <repository_url>
2. Navigate to the project directory: cd restaurant-rating-prediction
3. Install dependencies: pip install -r requirements.txt
4. Run the Jupyter notebook: jupyter notebook

**Dependencies**
Python 3.7+
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook
