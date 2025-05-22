# 🌟Vehicle Price Prediction🌟
## Vehicle Price Prediction & Market Analysis

### Overview
This project leverages the "Vehicle Dataset 2024" to explore the new vehicle market, perform comprehensive Exploratory Data Analysis (EDA), and develop predictive models for vehicle prices. It's designed to demonstrate various data science applications, from data cleaning to advanced regression techniques.

### Dataset
The "Vehicle Dataset 2024" offers a detailed snapshot of new vehicles, including SUVs, cars, trucks, and vans, currently available in the market. It's a rich resource for anyone looking to practice and apply data science skills.

Size: Contains 1002 entries across 18 columns.

***Column Descriptors***

🎯***name:*** The full name of the vehicle, including make, model, and trim.

🎯***description:*** A brief description of the vehicle, often including key features and selling points.

🎯***make:*** The manufacturer of the vehicle (e.g., Ford, Toyota, BMW).

🎯***model:*** The model name of the vehicle.

🎯***type:*** The type of the vehicle, which is "New" for all entries in this dataset.

🎯***year:*** The year the vehicle was manufactured.

🎯***price:*** The price of the vehicle in USD.

🎯***engine:*** Details about the engine, including type and specifications.

🎯***cylinders:*** The number of cylinders in the vehicle's engine.

🎯***fuel:*** The type of fuel used by the vehicle (e.g., Gasoline, Diesel, Electric).

🎯***mileage:*** The mileage of the vehicle, typically in miles.

🎯***transmission:*** The type of transmission (e.g., Automatic, Manual).

🎯***trim:*** The trim level of the vehicle, indicating different feature sets or packages.

🎯***body:*** The body style of the vehicle (e.g., SUV, Sedan, Pickup Truck).

🎯***doors:*** The number of doors on the vehicle.

🎯***exterior_color:*** The exterior color of the vehicle.

🎯***interior_color:*** The interior color of the vehicle.

🎯***drivetrain:*** The drivetrain of the vehicle (e.g., All-wheel Drive, Front-wheel Drive).


### Data Science Applications
This rich dataset enables a wide array of data science applications:

🪄***Price Prediction:*** Develop regression models to accurately predict vehicle prices based on attributes like make, model, year, and mileage.

🪄***Market Analysis:*** Identify trends in vehicle types, brands, and pricing dynamics, perform market segmentation, and gain insights into consumer preferences.

🪄***Descriptive Statistics:*** Conduct thorough descriptive statistical analyses to summarize and understand the central tendencies, spread, and distributions of key features.

🪄***Visualization:*** Create compelling visualizations to illustrate the distribution of prices, mileage, and other features across different vehicle types, fuels, and drivetrains.

🪄***Data Cleaning:*** Practice essential data cleaning techniques, including handling missing values, identifying and addressing outliers, and transforming data for optimal analysis.

🪄***Feature Engineering:*** Innovate by developing new, impactful features (e.g., price per year, mileage per year) to enhance model performance and uncover deeper patterns.


### Exploratory Data Analysis (EDA)
The EDA phase in the Vehicle_Price_Prediction.ipynb notebook involves:

⚡***Initial Data Inspection:*** Checking for missing values (NaN values) and reviewing data types for each column.

⚡***Descriptive Statistics:*** Generating statistical summaries for numerical columns to understand their range, mean, standard deviation, etc.

⚡***Univariate Analysis:*** Analyzing the distribution of individual features like price, mileage, year, cylinders, and doors using histograms, box plots, and count plots.

⚡***Bivariate Analysis:*** Exploring relationships between price and other features (e.g., make, body, fuel, transmission, drivetrain, exterior_color, interior_color). This helps identify potential correlations and influences on vehicle pricing.

⚡***Outlier Detection:*** Visual identification of outliers in numerical features that might require special handling.


### Data Preprocessing
✔️***Handling Missing Values:*** Strategies to address any missing data points (though the current dataset might be relatively clean).

✔️***Categorical Encoding:*** Converting categorical features (like make, model, fuel, etc.) into numerical representations suitable for machine learning models, typically using one-hot encoding or label encoding.

✔️***Feature Selection:*** Identifying and selecting the most relevant features for predicting vehicle prices, potentially using techniques like SelectKBest with f_regression.

✔️***Train-Test Split:*** Splitting the processed data into training and testing sets for model development and evaluation.


### Price Prediction Models
This project explores various regression models to predict vehicle prices, including:

⚡***Linear Regression:*** A baseline model for understanding linear relationships.

⚡***Decision Tree Regressor:*** A non-linear model capable of capturing complex decision rules.

⚡***Random Forest Regressor:*** An ensemble method that combines multiple decision trees to improve accuracy and reduce overfitting.


### Model Tuning
***Hyperparameter tuning*** (e.g., using GridSearchCV) is applied to optimize the performance of the Decision Tree and Random Forest models.


### Results
The performance of the predictive models is evaluated using standard regression metrics:

🎯***Mean Squared Error (MSE):*** Measures the average squared difference between the estimated values and the actual value.

🎯***R-squared (R^2) Score:*** Indicates how well the model's predictions fit the observed data. A higher R^2value (closer to 1) indicates a better fit.

***Example Results*** (from notebook evaluation):
Tuned Decision Tree: MSE: ~126,121,141.75, R^2: ~0.505

Tuned Random Forest: MSE: ~126,014,601.83, R^2: ~0.506

These results suggest that while the models can explain about 50% of the variance in vehicle prices, there's still room for improvement, potentially through more advanced feature engineering, exploring other models (like gradient boosting), or acquiring more data.

