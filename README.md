# Data-Preprocessing

  # one hot encoding and label encoding

🔹 1. Importing Required Libraries
pandas is used for data manipulation and analysis.
LabelEncoder and OneHotEncoder from sklearn.preprocessing are used to perform label encoding and one-hot encoding respectively.

🔹 2. Loading the Dataset
Loads the dataset named data1.csv into a DataFrame ds

🔹 3. Dataset Overview
Provides information on columns, data types, and non-null counts.
Gives statistical summary (mean, std, min, max, etc.) of numerical columns.

🔹 4. Installing scikit-learn (if not installed)
Ensures scikit-learn is available for machine learning and preprocessing.

🔹 5. Handling Missing Values (Mean Imputation)
Replaces missing values in the Age and Salary columns with their mean.

🔹 6. Checking the Cleaned Data
Displays the updated dataset after handling missing values.

🔹 7. One-Hot Encoding Using scikit-learn
Converts the Country column into a binary matrix using One-Hot Encoding.
sparse_output=False returns a dense array.

🔹 8. Creating One-Hot Encoded DataFrame
Uses get_feature_names_out() to name the new columns.
Creates a new DataFrame (encoded_df) with encoded features.

🔹 11. Concatenating Encoded Columns with Original Dataset
Merges the encoded columns back to the original dataset.

🔹 12. Dropping Original Categorical Column
Drops the original Country column since it's now encoded.

🔹 13. Label Encoding for Target Variable
Converts the Purchased column into numeric form using label encoding.

🔹 14. Feature Scaling
Normalizes the Age and Salary columns to have mean = 0 and std = 1.

🔹 15. Splitting Independent and Dependent Variables
x contains the features; y contains the target variable (Purchased).

🔹 16. Splitting Data into Train and Test Sets
Splits the dataset into training and testing sets using an 80-20 ratio.

 17. Viewing the Test Target Data
     Displays the target labels of the test set.

     # Ordinal Encoding
 🔹 1. Import Required Library    
 Imports the pandas library for data handling and analysis.

 🔹 2. Create Sample Dataset
 Creates a dataset using a dictionary with columns:
 CostmorID: Unique identifier.
 Education_Level: Ordered educational qualifications.
 Product_Quality: Quality ratings.
 Satisfaction_Level: Customer satisfaction responses.
 Converts this dictionary into a pandas DataFrame named df.

 🔹 3. View the Original Data
Displays the raw, unencoded dataset.

🔹 4. Define Order for Ordinal Columns
Manually specifies the logical order of values for each column.
Education_Level: from least to highest degree.
Product_Quality: from worst to best.
Satisfaction_Level: from least to most satisfied.

🔹 5. Import OrdinalEncoder from scikit-learn
Imports the OrdinalEncoder class from sklearn.preprocessing.

🔹 6. Initialize the OrdinalEncoder with Defined Orders
Initializes the encoder and provides the predefined order of categories for each feature.
Ensures that encoding reflects the true ordinal relationships.

🔹 7. Apply Ordinal Encoding
Transforms the three ordinal columns into numeric format using the defined category order.
Encoded values are assigned back to the same columns in the DataFrame.

🔹 8. View the Encoded Data
Displays the DataFrame with transformed numeric values for the ordinal features.
























