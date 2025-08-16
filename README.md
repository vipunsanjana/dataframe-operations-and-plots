````markdown
# Data Science with Python – Pandas, NumPy, Matplotlib & Seaborn

This repository contains my practice code for **data analysis and visualization** using Python.  
It covers key operations in **Pandas, NumPy, Matplotlib, and Seaborn** with practical examples.

---

## 📌 Contents
- **Pandas Basics**
  - Creating DataFrames
  - Selecting rows & columns
  - Using `iloc`, indexing, reindexing
  - Dropping rows/columns
  - Concatenation and merging
  - Value counts

- **NumPy**
  - Generating random arrays
  - Converting into DataFrames

- **Matplotlib**
  - Line plots
  - Scatter plots
  - Customizing labels and titles

- **Seaborn**
  - Heatmaps for correlation & matrices

---

## 📊 Sample Visualizations

- **Line Plot**

  ```python
  plt.plot([1,2,3,4],[10,25,32,58])
  plt.xlabel("Month")
  plt.ylabel("Price")
  plt.title("Price against the months")
  plt.show()
````

* **Heatmap**

  ```python
  sns.heatmap(df, annot=True)
  plt.show()
  ```

---

## 🚀 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/pandas-playground.git
   cd pandas-playground
   ```

2. Install requirements

   ```bash
   pip install -r requirements.txt
   ```

3. Run the scripts in Jupyter Notebook or directly with Python.

---

## 📦 Requirements

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📌 Author

👨‍💻 **Vipun Sanjana**
Full-Stack & DevOps Engineer | Exploring Data Science & AI
