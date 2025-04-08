# M1P12-Capstone-Project
# Movie Runtime Analysis Capstone Project
# Overview
This capstone project analyzes a movie dataset using various data science tools in Python. The objective was to showcase skills in data processing, statistical analysis, SQL, and data visualization.

# Tools & Libraries Used

- **Python**
- **NumPy** – For numerical operations
- **Pandas** – For data manipulation
- **Matplotlib & Seaborn** – For data visualization
- **Statistics** – For computing median
- **SQLite (via sqlite3)** – For SQL queries
- **Requests** – (Imported for optional web access)

---

# Dataset
- **File**: `movies.csv`
- **Columns**:
  - `movieId`
  - `title`
  - `genres`

A new column, `runtime_minutes`, was generated using NumPy for analysis.

---

# Key Tasks

- Loaded and explored the movie dataset
- Generated random movie runtimes using NumPy
- Calculated the average and median runtime
- Queried the dataset using SQL to find genres with the longest average runtime
- Visualized the distribution of movie runtimes

---

# Insights

- Movie runtimes are normally distributed between 80 to 180 minutes.
- Certain genres (e.g., Drama, Action) tend to have longer runtimes.
- SQL queries help summarize trends quickly.

