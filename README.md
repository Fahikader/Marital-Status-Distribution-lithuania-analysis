# Lithuanian Family Status Analysis (2023)

This project analyzes Lithuanian census data from `SeiminePadetis.csv` to study the distribution of **family and marital statuses** in 2023 using Python, Pandas, and Matplotlib.

---

## 📂 Dataset
The dataset contains demographic and family information. After renaming and cleaning, the key columns are:
- `Record_id` – Unique record identifier  
- `Gender` – Gender of the person  
- `Family_Status` – Marital/family status  
- `Number_of_children` – Total number of children  
- `Census_year` – Census year  

---

## ⚙️ Analysis Process
1. Load the dataset:
   ```python
   import pandas as pd
   import matplotlib.pyplot as plt
   df = pd.read_csv("SeiminePadetis.csv")
