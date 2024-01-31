import pandas as pd

# Assuming your dataset is in a CSV file named 'salaries.csv'
file_path = 'path_to_your_file/salaries.csv'

# Read the dataset into a pandas DataFrame
df = pd.read_csv(file_path)

# Display the number of rows and columns
print("Number of rows: ", df.shape[0])
print("Number of columns: ", df.shape[1])

# Display data types of each column
print("\nData types of each column:")
print(df.dtypes)

# Check for missing values in each column
print("\nMissing values in each column:")
print(df.isnull().sum())
