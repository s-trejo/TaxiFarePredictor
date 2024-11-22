# Taxi Fare Predictor

**Final Project for Introduction to Data Science at the University of Florida**

## Project Description
This project aims to predict NYC taxi fares using a neural network, leveraging features such as pickup and drop-off locations, times, distances, and other spatial-temporal data. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, and model building to uncover insights and develop an accurate predictive model.

---

## Project Plan

### 1. Data Preprocessing
- **Objective**: Clean and prepare the dataset for analysis and modeling.
  - Remove missing values and outliers.
  - Engineer features (e.g., distance using Haversine formula, time-based features like hour/day).
  - Normalize numerical features (latitude, longitude, distance).

### 2. Exploratory Data Analysis (EDA)
- **Objective**: Understand the dataset and identify patterns.
  - Perform univariate analysis (e.g., fare distribution, distance distribution).
  - Conduct bivariate analysis (e.g., correlation between fare and distance).
  - Visualize pickup and drop-off hotspots on a map of NYC.

### 3. Data Visualization
- **Objective**: Create visual insights for understanding and presentation.
  - Heatmaps for pickup/drop-off density.
  - Fare trends by time of day and day of the week.
  - Scatter plots showing relationships between distance and fare.

### 4. Model Building
- **Objective**: Build and train a neural network to predict taxi fares.
  - Develop a neural network architecture with input, hidden, and output layers.
  - Use Mean Absolute Error (MAE) as the loss function.
  - Implement training with early stopping and learning rate scheduling.

### 5. Model Evaluation and Tuning
- **Objective**: Optimize model performance.
  - Split the data into training, validation, and test sets.
  - Experiment with hyperparameters (e.g., layers, learning rate, batch size).
  - Evaluate the model using metrics like MAE and visual error analysis.

### 6. Analysis and Recommendations
- **Objective**: Derive actionable insights from the model and data.
  - Identify high-demand zones and peak periods.
  - Analyze spatial-temporal trends for fare patterns.
  - Recommend strategies for fare pricing and taxi allocation.

---

## Deliverables
1. **Codebase**: Jupyter Notebooks and Python scripts for each step of the project.
2. **Final Report**: A PDF summarizing the methodology, findings, and actionable insights.
3. **Visualizations**: Graphs, charts, and maps showcasing key trends and patterns.

---

## Team Members
- **Joshua Arroyo**
- **Samuel Trejo**