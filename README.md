#  Developer Survey Analysis (Udacity Data Science Project)

##  Overview
This project analyzes data from the **Stack Overflow Developer Survey 2024** to uncover key insights about:
- The most popular programming languages.  
- The relationship between **years of experience and salary**.  
- How **remote vs in-person work** affects compensation.  
- Developer **job satisfaction** patterns.

The goal is to communicate meaningful findings using clear visuals and storytelling suitable for both technical and non-technical audiences.

---

##  Files in the Repository
| File/Folder | Description |
|--------------|-------------|
| `stackoverflow_analysis.ipynb` | Main Jupyter Notebook containing data loading, cleaning, analysis, and visualizations. |
| `data/` | Folder containing the survey CSV dataset (not included due to size limits). |
| `figures/` | Folder containing exported plots and charts. |
| `README.md` | Project documentation (this file). |
---

##  Libraries Used
To reproduce the analysis, you’ll need the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn pathlib
```
---
## Core libraries:
| Library      | Purpose                                           |
| ------------ | ------------------------------------------------- |
| `pandas`     | Data cleaning, manipulation, and summarization    |
| `numpy`      | Numerical computations and statistical operations |
| `matplotlib` | Core visualization library                        |
| `seaborn`    | High-level plotting and statistical visualization |
| `pathlib`    | File and path management for cleaner I/O          |
---
## Key Findings
| Area of Analysis                       | Key Takeaway                                                                                       |
| -------------------------------------- | -------------------------------------------------------------------------------------------------- |
|  **Programming Language Popularity** | Python remains the top language, followed by JavaScript and SQL.                                   |
|  **Salary by Language**              | Developers working with **Go** and **Rust** have the highest median salaries.                      |
|  **Median Salary by Country**        | The **U.S.** and **Switzerland** lead globally in developer pay.                                   |
|  **Remote vs In-person Work**        | Remote and hybrid developers earn **10–15% higher median salaries** compared to in-person workers. |
|  **Job Satisfaction**                | Developers with flexible or remote setups report the highest satisfaction levels.                  |
---
## Analysis Highlights

Below are the main visualizations produced in this project:

1. Top 12 Programming Languages by Popularity
Visual: Horizontal bar chart showing frequency of languages used.

2. Median Salary by Country (Top 15)
Visual: Horizontal bar chart comparing salary medians for countries with 100+ respondents.

3. Experience vs Salary Relationship
Visual: Scatter plot on a log scale showing correlation between years of experience and salary.

4. Median Salary by Programming Language
Visual: Horizontal bar chart ranking languages by compensation.

5. Compensation Distribution by Work Setup
Visual: Boxplot comparing salary ranges across Remote, Hybrid, and In-person categories.

---
## Acknowledgements

- Dataset: Stack Overflow Developer Survey 2024, publicly available via Stack Overflow Insights

- Educational context: Project completed as part of the Udacity Data Scientist Nanodegree.

- Visual and analytical inspiration: Drawn from discussions and kernels on Kaggle and Stack Overflow.

