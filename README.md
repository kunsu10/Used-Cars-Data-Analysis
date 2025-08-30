# Used_Cars_Data_Analysis
This project performs an exploratory data analysis on a used car dataset to understand price factors. It covers data cleaning, feature engineering, and a detailed analysis of key relationships. The analysis reveals a strong negative correlation between a car's age and its price.

**Key Features and Analysis**

The project covers a comprehensive data analysis workflow, including:

Data Cleaning and Preprocessing: 

- Handled missing values, removed unnecessary columns (S.No., New_Price, etc.), and converted data types to ensure they are suitable for analysis.

Feature Engineering: 

- Created new columns such as Brand (extracted from the car name) and Car Age (calculated from the year of manufacture) to derive more meaningful insights.

Exploratory Data Analysis (EDA):

- Univariate Analysis: Explored the distribution of individual variables like Price, Mileage, Engine, and Power to identify central tendencies and outliers.

- Bivariate Analysis: Analyzed the relationships between pairs of variables, such as Location vs. Fuel_Type and Transmission vs. Brand, to uncover patterns and preferences.

- Multivariate Analysis: Examined the correlations between multiple numerical variables, providing a deeper understanding of how they interact.

**Key Findings**

The analysis revealed several significant insights into the used car market:

Price and Age: 

- There is a strong negative correlation between Price and Car Age (-0.68). This means that as a car gets older, its price tends to decrease.

Price and Performance: 

- The analysis showed a positive correlation between Price and both Power (0.46) and Engine (0.34). This indicates that cars with more powerful or larger engines are generally more expensive.

Engine and Power: 

- A strong positive correlation was found between Engine and Power (0.82), which is expected since a larger engine typically generates more power.

Mileage and Efficiency: 

- The analysis suggests a weak negative correlation between Mileage and Car Age (-0.37) and Mileage and Engine (-0.23), implying that older cars and those with larger engines tend to have lower fuel efficiency.

Popularity Trends: 

- The most common cars in the dataset are 5-seaters with a manual transmission. Maruti, Hyundai, and Honda are the most frequently listed brands.

**Technologies Used**

- Python

- Pandas: For data manipulation and analysis.

- NumPy: For numerical operations.

- Matplotlib and Seaborn: For data visualization.
