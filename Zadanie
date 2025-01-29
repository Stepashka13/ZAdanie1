import pandas as pd
import openpyxl
import math



df_excel = ("Players.xlsx")

df = pd.read_excel(df_excel)

print("Исходные данные:")
print(df)

column_name = 'Players'
numeric_values = df[column_name].dropna()
numeric_values = numeric_values[pd.to_numeric(numeric_values, errors='coerce').notnull()]
total_sum = sum(numeric_values)
sredne = total_sum/15
print("")
print("")



print("Информация про Players: ")
print("")
print("")
print("Среднее арифмитическое: ")
print(sredne)
raznica = max(numeric_values) - min(numeric_values)
print("")

maximum = max(numeric_values)
minimum = min(numeric_values)

print("Макс. значение: ")
print(maximum)
print("")
print("Мин. значение: ")
print(minimum)
print("")
print("Разница между макс. значением и мин. значением: ")
print(raznica)
