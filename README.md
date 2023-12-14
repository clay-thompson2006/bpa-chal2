# bpa-chal2
import csv
import pandas as pd

df = pd.read_csv("Sample_Data_Age.csv")
print(df)
result=df(df['Age'] >64)
print(result)



df_sorted = df.sort_values(by='Name')
df_sorted.to_csv('homes_sorted.csv', index=False)
