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

# CountVectorizer
- ![Screenshot 2024-12-29 at 5 27 02 PM](https://github.com/user-attachments/assets/32420288-edc8-4f6e-aaf2-e3567be2a7dc)
## fit()
- ![Screenshot 2024-12-29 at 5 29 09 PM](https://github.com/user-attachments/assets/6e04357a-84f4-46dd-b4db-a750e8ed1406)
## transform()
- ![Screenshot 2024-12-29 at 5 30 11 PM](https://github.com/user-attachments/assets/e6aecc56-2ff5-4c9d-a09b-c3d442b0199f)
# TfidfTransformer
- TfidfTransformer is a part of the scikit-learn library used to convert raw word counts (from tools like CountVectorizer) into TF-IDF (Term Frequency-Inverse Document Frequency) values. It helps emphasize important words in a document while reducing the weight of common but less meaningful words.
- ![Screenshot 2024-12-29 at 5 34 56 PM](https://github.com/user-attachments/assets/9d722199-0a47-4789-8cd2-f62aac42ebee)

# Can do transform() without fit()?
- The short answer is: No, you cannot directly call transform without first calling fit on most transformers or models in libraries like scikit-learn

# Distingushing TP,TN,FP,FN
- ![Screenshot 2025-01-04 at 11 21 32 AM](https://github.com/user-attachments/assets/5fd52fe2-1da9-4229-a611-c27d40d2d619)






