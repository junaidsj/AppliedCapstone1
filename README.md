### 🚀 JSON Normalization and Rocket Data Filtering

After loading the JSON response using `response.json()`, we use `pd.json_normalize()` to convert nested JSON data into a flat Pandas DataFrame:

```python
from pandas import json_normalize

# Assuming 'data_json' is the decoded JSON object
data = json_normalize(data_json)
