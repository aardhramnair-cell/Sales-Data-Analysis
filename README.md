import pandas as pd

df = pd.read_csv("sales.csv")

print("Total Sales:")
print(df["Sales"].sum())

print("Average Sales:")
print(df["Sales"].mean())

print("Highest Sales:")
print(df["Sales"].max())
