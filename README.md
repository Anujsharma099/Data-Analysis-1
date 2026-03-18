Automobile Price & Specification Analysis
📌 Project Objective
This project explores the UCI Automobile Dataset to identify the key physical and engine-related characteristics that drive a vehicle's market price. The analysis follows a standard Data Science workflow: Data Cleaning, Exploratory Data Analysis (EDA), and Feature Engineering.

🛠️ Key Skills & Tools
Language: Python

Libraries: - Pandas: Data manipulation and cleaning.

NumPy: Numerical operations.

Matplotlib & Seaborn: Advanced data visualization.

Workflow: Handling non-standard missing values, data type conversion, and statistical aggregation.

📊 Key Insights from the Analysis
Price Drivers: There is a significant price variation based on body-style. Hardtop and Convertible models command the highest average prices, exceeding $20,000, while Hatchbacks are the most budget-friendly.

Data Integrity: Identified and handled non-standard missing values (represented as ? in the raw data). Implemented mean imputation for numerical columns (bore, stroke, horsepower) and mode imputation for categorical data (num-of-doors).

Engine Performance: Converted engine specification columns to numerical types to enable quantitative analysis of horsepower, bore, and peak-rpm.

Efficiency Metric: Engineered a new feature, cmb_mpg (Combined MPG), by averaging city and highway mileage to provide a more holistic view of fuel efficiency.

🚀 How to Run
Clone this repository.

Install the required dependencies:

Bash
pip install pandas numpy matplotlib seaborn
Open the Jupyter Notebook:

Bash
jupyter notebook data_analysis_1.ipynb
📁 Repository Structure
data_analysis_1.ipynb: The main notebook containing all Python code, visualizations, and documentation.

automobile.csv: The raw dataset containing 205 entries and 26 car attributes.
