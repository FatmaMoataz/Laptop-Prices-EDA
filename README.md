# Laptop Prices EDA & Feature Engineering

This project contains a full exploratory data analysis (EDA) and preprocessing of a laptop prices dataset. The notebook demonstrates data cleaning, visualization, feature engineering, and preparation for machine learning tasks.

## Files
- `Laptop_Prices_EDA.ipynb` : The Colab notebook with all EDA steps, preprocessing, and plots.
- `laptop_prices.csv` : The dataset file.

## Project Steps
1. **Import Libraries**  
   Numpy, Pandas, Seaborn, Matplotlib, and Google Colab files for data handling and visualization.

2. **Upload and Read Dataset**  
   Upload the CSV file and preview the first rows to understand the data structure.

3. **Inspect Dataset**  
   Check data types, missing values, and duplicate rows.

4. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics for numeric and categorical columns.  
   - Histograms and boxplots to visualize distributions and detect outliers.  
   - Correlation heatmap to understand numeric feature relationships.  
   - Scatter plots for categorical feature relationships.

5. **Handle Missing Values**  
   Imputation of missing numeric values using median values.

6. **Encode Categorical Variables**  
   Convert text columns into numeric using one-hot encoding.

7. **Scale Numeric Features**  
   StandardScaler is applied for normalization.

8. **Target and Features Separation**  
   Target: `SecondaryStorage`  
   Features: All other columns.

9. **Feature Engineering**  
   - Creating price categories (Low, Medium, High) using quantiles.  
   - Optional new features like total storage or interactions between CPU, RAM, and GPU.

## How to Run
1. Open the notebook in Google Colab.  
2. Upload `laptop_prices.csv` when prompted.  
3. Run all cells to reproduce the analysis, visualizations, and preprocessing steps.
