# How Programming Languages Affect Salaries and Remote Work
**Udacity Data Science Blog Post Project**  
**Author:** Ansam Nawar

## Overview
This repository contains a reproducible analysis of the Stack Overflow Developer Survey (2024 public responses). The project examines language popularity, median salaries by language and country, and remote vs on-site differences. Visual style is minimal and Medium-friendly.

## Files
- `stack_overflow_analysis.py` — Analysis script (also notebook-ready; use `# %%` cell markers).
- `data/` — (not included) put `survey_results_public.csv` here (download from StackOverflow Insights).
- `figures/` — Generated PNGs after running the script/notebook.
- `data_science_blog_post_stackoverflow.md` — Medium-style blog post draft (edit & paste into Medium).

## How to run (local)
1. Clone or download this repo.
2. Put the Stack Overflow CSV into `data/survey_results_public.csv`. Download from: https://survey.stackoverflow.co/2024
3. (Optional but recommended) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # macOS / Linux
   venv\\Scripts\\activate    # Windows PowerShell
   pip install pandas matplotlib
