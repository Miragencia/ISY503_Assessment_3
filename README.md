# ISY503_Assessment_3
Repository for the 3rd Assessment of the group of Ksenia, Sabrina and Farhan.

# Load the data
The following code can be used to import a merged CSV file containing 8000 samples:

```python
import pandas as pd

data = pd.read_csv('https://raw.githubusercontent.com/Miragencia/ISY503_Assessment_3/main/merged_files/merged_review_files.csv',
                   sep=';', encoding='utf8')
```

Data source: https://www.cs.jhu.edu/~mdredze/datasets/sentiment/index2.html
