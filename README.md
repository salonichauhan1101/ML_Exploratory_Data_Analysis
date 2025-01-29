# 🚗 Fuel Economy Data Analysis 

## 📌 Overview
This project focuses on **Exploratory Data Analysis (EDA)** of a **Fuel Economy Dataset**, aiming to understand trends in fuel efficiency (`UCity` - Unadjusted City MPG) across various vehicle attributes. The analysis involves **data visualization, statistical insights, correlation studies, and predictive modeling considerations**.

## 📊 Key Objectives
- Perform **data cleaning** and handle missing values.
- Analyze and visualize **fuel efficiency trends** across various independent variables.
- Investigate relationships between **engine specifications, fuel type, vehicle class, and transmission types**.
- Examine **historical trends in fuel consumption** and **emissions data**.
- **Identify and remove irrelevant or redundant features** for predictive modeling.
- Discuss the **most suitable machine learning approach** for predicting `UCity`.

## 📂 Dataset Details
- Source: [EPA Fuel Economy Data](https://www.fueleconomy.gov)
- The dataset contains:
  - **Numeric Variables** (e.g., `UCity`, `highway08`, `barrels08`, `co2`, etc.)
  - **Categorical Variables** (e.g., `fuelType`, `VClass`, `trany`, `make`, etc.)
  - **Missing Values** handled and visualized appropriately.

## 📌 Key Analyses Performed
### 📈 Exploratory Data Analysis (EDA)
- **Data Summary:** Overview of missing values, data distributions, and statistical summaries.
- **Visualization of `UCity` trends:**
  - UCity vs Year
  - UCity Histogram
  - UCity vs Fuel Type
- **Analysis of Independent Variables:**
  - Engine Displacement (`displ`) vs UCity
  - Cylinders vs Fuel Efficiency
  - Vehicle Class (`VClass`) Analysis
  - Fuel Type Trends Over the Years
  - Transmission Types (`trany`) Evolution
- **Correlation Analysis:**
  - Heatmap of `UCity` with major variables (`co2`, `barrels08`, etc.)
  - Impact of transmission type and engine size on fuel efficiency.

### 🔍 Machine Learning Approach
- Justification for treating `UCity` as a **dependent variable**.
- Discussion on **Regression vs Classification Models**.
- Selection of **important features** for a predictive model.
- Methods to **avoid overfitting and underfitting** in ML models.

## 📌 Notebooks & Code
- **Assignment Notebook:** [Fuel_Economy_Analysis.ipynb](./Fuel_Economy_Analysis.ipynb)
- **Dataset:** `vehicles.csv`
- **Visualizations & Insights:** Generated using `Matplotlib` & `Seaborn`

## 🛠 Technologies Used
- **Python** (`pandas`, `numpy`, `matplotlib`, `seaborn`)
- **Jupyter Notebook**
- **GitHub** for version control.

## 📌 How to Run the Notebook
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/Fuel-Economy-EDA.git
   cd Fuel-Economy-EDA
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook Fuel_Economy_Analysis.ipynb
   ```

## 📌 Key Insights from Analysis
- **Fuel efficiency (`UCity`) has improved significantly after 2010**, influenced by the rise in **hybrid and electric vehicles**.
- **Smaller engine displacements and fewer cylinders** contribute to **better fuel efficiency**.
- **Manual transmissions have slightly better fuel economy**, but automatic cars dominate in count.
- **CO2 emissions and fuel consumption (`barrels08`) show strong negative correlation** with `UCity`, confirming their impact on mileage.
- **The number of gas-guzzling vehicles (`guzzler`) has decreased over time**, aligning with the trend of fuel-efficient cars.

## 🚀 Future Work
- Build a **predictive model** using **Linear Regression, Decision Trees, or Neural Networks**.
- Implement **Feature Engineering** to enhance model accuracy.
- Compare different **fuel types and emissions regulations** over time.
