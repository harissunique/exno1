# Exno:1
Data Cleaning Process
## Reg No: 212223230073
## Name: HarishKumar R

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
```py
import pandas as pd
df=pd.read_csv("/content/Data_set.csv")

df.head(5)
![](./head.png)


df.tail(3)

df.info()

df.describe()

df.isnull()

df.notnull()

df.dropna(axis=1)

dfs=df[df['rating']>8]
dfs

df.iloc[[1,3,6],[1,4]]

df=df.fillna(0)
df
```


# Result
          <<include your Result here>>
