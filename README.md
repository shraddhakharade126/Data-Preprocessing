# Data-Preprocessing

one hot encoding and label encoding

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
















