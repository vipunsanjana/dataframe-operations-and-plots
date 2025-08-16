
# Data Science with Python – Pandas, NumPy, Matplotlib & Seaborn

Welcome to my Data Science Practice Repository.
This project contains exercises and examples of data analysis and visualization using Python’s most popular libraries.

---

## Contents

**Pandas**

* Creating and exploring DataFrames
* Selecting rows and columns (using iloc, indexing, reindexing)
* Dropping rows and columns
* Concatenation and merging
* Value counts and summaries

**NumPy**

* Generating random arrays
* Converting arrays into DataFrames

**Matplotlib**

* Line plots
* Scatter plots
* Adding labels, titles, and figure sizes

**Seaborn**

* Heatmaps for data visualization
* Annotated matrices

---

## Sample Visualizations

**Line Plot Example**
The following code creates a line plot of prices across months:

```
import matplotlib.pyplot as plt

L1 = [1, 2, 3, 4]
L2 = [10, 25, 32, 58]

plt.plot(L1, L2, marker="o")
plt.xlabel("Month")
plt.ylabel("Price")
plt.title("Price against the Months")
plt.show()
```

Output: A simple line chart showing price variation with months.

---

**Heatmap Example**
The following code generates a heatmap of location distances:

```
import seaborn as sns
import matplotlib.pyplot as plt
import pandas as pd

df = pd.DataFrame({"Loc1":[0,10,20], "Loc2":[10,0,15], "Loc3":[20,15,0]}, 
                  index=["Loc1","Loc2","Loc3"])

sns.heatmap(df, annot=True, cmap="YlGnBu")
plt.title("Location Distance Matrix")
plt.show()
```

Output: A colored heatmap showing location distances in a matrix form.

---

## Getting Started

1. Clone the repository:
   `git clone https://github.com/vipunsanjana/dataframe-operations-and-plots.git`
   `cd dataframe-operations-and-plots`

2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn`

3. Run the code either in Jupyter Notebook or directly with Python.

---

## Requirements

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Author

Vipun Sanjana
Full-Stack & DevOps Engineer | Exploring Data Science & AI

---
