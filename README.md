# 🎯 What You're Aiming For

In this checkpoint, we are going to work on the 'Customer Purchases History' dataset provided by Kaggle.

## Dataset Description

This dataset contains historical records for customer purchases from a supermarket X. The objective is to find the association rules to help supermarket owners find new marketing plans to improve their sales.

toy_dataset = [['Skirt', 'Sneakers', 'Scarf', 'Pants', 'Hat'],
               ['Sunglasses', 'Skirt', 'Sneakers', 'Pants', 'Hat'],
               ['Dress', 'Sandals', 'Scarf', 'Pants', 'Heels'],
               ['Dress', 'Necklace', 'Earrings', 'Scarf', 'Hat', 'Heels', 'Hat'],
               ['Earrings', 'Skirt', 'Skirt', 'Scarf', 'Shirt', 'Pants']]

➡️ Dataset link: [https://drive.google.com/file/d/1GO28zbMfhy6G6COiLDGr90Bk6Ig0hV6K/view?usp=sharing]

🚧 NOTE: Each row corresponds to one purchase.


# ℹ️ Instructions

### Import Data and Perform Basic Data Exploration

- Load the dataset and explore its basic structure and statistics.
- Display general information and summary statistics about the dataset.

### Data Preparation

- Import the dataset and perform basic exploration.
- Handle corrupted and missing values.
- Encode categorical features.
- Handle outliers and remove duplicates.
- Select the target variable and feature set.
- Split the dataset into training and test sets.

### Build and Train an SVM Model

- Construct and train an SVM model on the training set.

### Evaluate Model Performance

- Assess the model performance on the test set using relevant evaluation metrics.

## 🛠️ Tools and Libraries

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **SciPy**: Scientific computing
- **Scikit-learn**: Machine learning algorithms

# Libraries Used

```
import pandas as pd
import plotly.express as px
from mlxtend.frequent_patterns import apriori, association_rules
frequent_itemsets = apriori(df, min_support=0.6, use_colnames=True)
rules = association_rules(frequent_itemsets, metric="lift", min_threshold=1)
```
