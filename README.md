# IPL-Data-Analysis

# 📊 IPL Data Analysis using NumPy and Matplotlib

This project is a beginner-friendly exploration of IPL (Indian Premier League) player data using **NumPy** for numerical computation and **Matplotlib** for data visualization.

The primary goal of this project is to **analyze and compare the salaries of IPL players across different seasons**, perform **basic matrix operations**, and understand how to **index, slice, and reshape data using NumPy**. Visualizations are used to help draw insights from the data.

The dataset includes salaries, games played, and performance points of well-known IPL players from **2015 to 2024**. Using this data, we:

- Converted raw lists into structured **NumPy matrices**
- Performed **indexing and slicing** to extract insights
- Calculated **salary-per-game ratios**
- Plotted **salary comparisons** over time for each player using line graphs

This project is a stepping stone into **data science and sports analytics**, and it's my **first project using NumPy and Matplotlib**.

---

## 🔧 Technologies Used
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📁 Dataset Overview
- **Seasons:** 2015 to 2024
- **Players:** Sachin, Rahul, Smith, Sami, Pollard, Morris, Samson, Dhoni, Kohli, Sky
- **Data Tracked:**  
  - Player Salaries  
  - Matches Played  
  - Points Scored

---

## 🧠 What I Learned
- Creating and reshaping NumPy arrays
- Indexing and slicing multi-dimensional arrays
- Converting raw player data into matrix format
- Accessing specific player-season data using dictionaries (`Pdict`, `Sdict`)
- Visualizing multiple salary trends with Matplotlib
- Using markers, legends, colors, and ticks in plots

---

## 📈 Sample Code Snippet

```python
plt.plot(Salary[0], c='green', ls='--', marker='s', ms=8, label=Players[0])
plt.xticks(list(range(0,10)), Seasons, rotation='vertical')
plt.legend()
plt.show()
```

---

## 📚 Next Steps
- Add bar charts for points comparison
- Include average salary per season
- Export graphs to image files
- Integrate Pandas for data cleaning

---
