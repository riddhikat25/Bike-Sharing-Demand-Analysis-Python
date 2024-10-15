# Bike-Sharing-Demand-Analysis-Python
The bike-sharing prediction project involves several key steps as outlined in the notebook:

1. **Libraries and Data Loading**:
   - Imported libraries include `pandas`, `matplotlib`, `seaborn`, `sklearn`, and `numpy`.
   - Loaded the dataset `day.csv` using `pandas`.

2. **Data Exploration**:
   - Displayed the shape and first few rows of the dataset to understand its structure.
   - Generated descriptive statistics to get a summary of numerical columns.
   - Checked for missing values to decide if data cleaning was needed (no missing values were found).

3. **Data Preprocessing**:
   - Converted the date (`dteday`) column to a proper datetime format and extracted components such as year, month, and day.
   - Dropped irrelevant columns (`holiday`, `dteday`, `instant`, `casual`, and `registered`) to simplify the dataset.
   - Renamed columns for better readability (e.g., `yr` to `year`, `hum` to `humidity`, and `cnt` to `count`).

4. **Model Preparation**:
   - Then proceeds to splitting the data into training and testing sets and evaluating a machine learning model for predicting bike-sharing demand.
