import pandas as pd

df = pd.read_csv("sales.csv")

print(df.isnull().sum())

df = df.drop_duplicates()

print(df.head())
