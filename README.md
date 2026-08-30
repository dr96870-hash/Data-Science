```python
import pandas as pd

df = pd.read_csv("bay_area_modeling_table.csv", low_memory=False)
print(df.shape)          # (34311, 65)
df.head()
```
