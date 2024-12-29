# Pandas DataFrame
The DataFrame constructor allows you to create a DataFrame from various data structures.

**import pandas as pd**

df = pd.DataFrame(data=None, index=None, columns=None, dtype=None, copy=None)

Parameters Explained:
- data (array-like, dict, Series, or DataFrame) : The data to populate the DataFrame.
Example: Dictionary of lists, NumPy arrays, Series, or another DataFrame.
- index (array-like or Index, optional)
Labels for the rows.
- columns (array-like or Index, optional)
Labels for the columns.
- dtype (data type, optional)
Enforce a specific data type for all columns.
- copy (bool, default False)
Copy data if it’s already a DataFrame or Series.

![Screenshot 2024-12-28 at 5 21 20 PM](https://github.com/user-attachments/assets/7a304983-a034-46d5-a3c1-b685274b510b)

## Common Parameters in Pandas DataFrame

**pd.read_csv()**

![Screenshot 2024-12-28 at 5 26 57 PM](https://github.com/user-attachments/assets/24732f33-061b-4557-a7d7-fbb3376dad66)

**df.drop()**

![Screenshot 2024-12-28 at 5 27 45 PM](https://github.com/user-attachments/assets/7ef70721-3c60-493c-8fb1-15841044f30b)

**df.dropna()**

![Screenshot 2024-12-28 at 5 30 57 PM](https://github.com/user-attachments/assets/0baf20f9-e9b0-416b-8309-21f830d29958)

## Describe

![Screenshot 2024-12-28 at 5 32 50 PM](https://github.com/user-attachments/assets/496df020-c3ef-494e-9989-3d14968185fa)

## plot(bins)

- In Pandas, the plot method is used to visualize data in DataFrames or Series, but bins is not a direct parameter of plot. Instead, bins is commonly used in histograms to control the number of bins (intervals) for data distribution visualization.
- bins=30: Divides the range of data into 30 equal-width intervals.
- ![Screenshot 2024-12-28 at 6 03 45 PM](https://github.com/user-attachments/assets/2144f33d-6828-4ff1-886f-20bb35090509)
- Fewer bins = Smoother representation; More bins = Detailed representation.


# Why should we add custom stopwords
- Informal Text Processing: To handle social media text, chat logs, or other casual sources.
- Noise Reduction: These words often add noise to the analysis and do not contribute meaningful insights.
- Improved Model Accuracy: By removing these terms, text classification or sentiment analysis models can focus on more meaningful words.

