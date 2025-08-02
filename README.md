 # 🏠 Housing Data Analysis

A simple exploratory data analysis (EDA) project focused on understanding housing trends like price, area, and bedroom distribution. The project uses Python libraries to analyze the data and visualize important patterns.

## 📁 Dataset Info

- *Filename:* Housing.csv  
- *Path:* /content/Housing.csv  
- *Includes:* Price, area (sq.ft), number of bedrooms, bathrooms, and other property features.

## 🧰 Libraries Used

```python
import pandas as pd  
import numpy as np  
import seaborn as sns  
import matplotlib.pyplot as plt  
%matplotlib inline

🔍 Steps Followed

Loaded the data using pandas

Checked data shape, types, null values

Separated numerical & categorical columns

Summarized stats using .describe(), .mean(), .std()


📊 Key Findings

Price: Right-skewed, with outliers. Range: ₹1.75M to ₹13.3M

Area: Also right-skewed; wide variation

Bedrooms: Most homes have 3 bedrooms; low variability

Price vs Area: Strong positive correlation

Price vs Bathrooms: Price rises with more bathrooms


📈 Visuals Used

Histogram for distributions

Boxplot for outlier detection

Countplot for bedroom frequency

Scatterplot for Price vs Area


📚 Insights

Median price is a better indicator due to outliers

Bedroom count alone doesn't determine price

Location, furnishing, and features impact pricing


🔧 Future Work

Add ML models to predict price
Explore more categorical attributes

Use tools like Streamlit for dashboarding

AUTHOR SHUMAILA SHAIKH


---

👩‍💻 Author: Shumaila Shaikh
