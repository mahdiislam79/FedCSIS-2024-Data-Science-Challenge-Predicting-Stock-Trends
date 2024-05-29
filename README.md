# FedCSIS-2024-Data-Science-Challenge-Predicting-Stock-Trends

Description
This repository contains the code and analysis for the FedCSIS 2024 Data Science Challenge, focused on predicting stock trends using a comprehensive dataset of financial indicators. The project involves data preprocessing, exploratory data analysis, and model building to achieve accurate stock trend predictions.


Import necessary libraries such as pandas, numpy, matplotlib, seaborn, missingno, scikit-learn, bokeh, holoviews, and hvplot for data manipulation, visualization, and machine learning.
Dataset Loading:

Load the training and test datasets along with the column names and group dictionaries.
Replace commas in floating point numbers to ensure correct data types.
Dataset Preprocessing:

Define column names and map group codes to sector names.
Handle missing values by identifying and replacing non-applicable or empty strings with 0.
Missing Values Analysis:

Conduct an initial analysis to count and understand the distribution of missing values in the dataset.
Use visualizations to identify patterns and correlations in the missing data.
Missing Values Correlation:

Utilize missingno library to create matrix and heatmap visualizations, revealing correlations between missing values in different columns.
Handling Empty Strings:

Replace 'Non-Applicable' or empty string values with 0 to ensure a clean dataset for analysis.
Correlation Analysis:

Calculate and visualize the correlation between various financial indicators and their derivatives (I and dI).
Assess the correlation between these indicators and the target variable, 'Class'.
Exploratory Data Analysis:

Perform additional exploratory data analysis to gain insights into the dataset's structure and relationships.
Visualize distributions and relationships between different financial indicators across various sectors.
How to Use
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/FedCSIS-2024-Stock-Trends.git
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook:

Open the Jupyter notebook containing the code and execute the cells sequentially to reproduce the analysis and results.
Conclusion
This project aims to leverage statistical learning and data mining techniques to predict stock trends effectively. The comprehensive approach, including thorough data preprocessing and exploratory analysis, lays the foundation for building robust prediction models.

For detailed code and analysis, refer to the Jupyter notebooks provided in this repository.
