# Analyzing and Predicting Restuarants Rating

Understanding the restaurant dataset to analyze the factors influence customer ratings by identifying relationships between variables such as cuisine type, average cost, votes, and restaurant ratings, while also building regression models to predict ratings based on these features.

## Objectives
1. Explore and clean the dataset to ensure consistency and accuracy.
2. Analyze patterns and trends across features like cuisines, cost, and votes.
3. Determine whether certain cuisines tend to receive higher ratings.
4. Build and evaluate regression models to predict restaurant ratings.

## Dataset Description
The dataset contains restaurant information across different cities and includes the following columns:
- Restaurant ID, Name, and Address  
- City and Country Code  
- Longitude and Latitude  
- Cuisines  
- Average Cost for Two  
- Currency  
- Has Table Booking / Online Delivery  
- Price Range  
- Aggregate Rating  
- Rating Text and Color  
- Votes  

## Workflow
1. **Data Cleaning:**  
   - Handled missing values
   - Data Type Conversion  

2. **Exploratory Data Analysis (EDA):**  
   - Explored rating distributions
   - Calculated the basic statistic measures for the numerical data type
   - Analyzed skewness in numerical data
   - Analyzed cuisines and other features and their relationship with ratings.  
   - Visualized data using histograms,  heatmaps, mapbox, boxplots, and bar charts.

3. **Feature Engineering:**    
   - Scaled numerical features where necessary
   - Extracted new features fom existing ones
   - Split the dataset into training and test data sets
   - Encoded boolean datatypes

4. **Model Building:**  
   Built multiple regression models to predict the restaurant rating:
   - Linear Regression
   - Decision tree regressor
   - Random Forest regressor  
   - XGBoost regressor  

   Each model was implemented using a pipeline for cleaner preprocessing and training.

5. **Model Evaluation:**  
   Models were evaluated using:
   - Mean Squared Error (MSE)
   - Root Mean Square Error (RMSE)
   - R-squared (R²)

   The Random Forest and XGBoost models performed best

## Tools and Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib and Seaborn  
- Scikit-learn  
- XGBoost  

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/abisolami/restaurant-rating-analysis.git
