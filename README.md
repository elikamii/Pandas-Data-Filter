# Pandas-Data-Filter
import pandas as pd

# 1. Create a sample dictionary data
data = {
    'Product': ['A', 'B', 'C', 'D', 'E'],
    'Price': [100, 250, 50, 300, 150],
    'InStock': [True, False, True, True, False]
}

# 2. Create the DataFrame
df = pd.DataFrame(data)

print("--- Original DataFrame ---")
print(df)

# 3. Filter: Select only rows where 'Price' is greater than 100
filtered_df = df[df['Price'] > 100]

print("\n--- Filtered DataFrame (Price > 100) ---")
print(filtered_df)
