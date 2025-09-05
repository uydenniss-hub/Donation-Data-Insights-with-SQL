# Donation Impact Analysis with SQL

## Overview
This project analyzes a dataset of assignments, donations, and donors using SQL queries. The goal is to uncover meaningful insights such as:
- Which assignments receive the highest total donation amounts
- How donations are distributed across regions and donor types
- The top assignment in each region based on impact score
- Trends in donation counts and donor engagement

## Key Features
- **Aggregation**: Summing and rounding total donation amounts per assignment and donor type.
- **Joins**: Combining data across `assignments`, `donations`, and `donors`.
- **Window Functions**: Ranking assignments within regions by impact score.
- **Filtering & Ordering**: Ensuring results highlight only the most impactful contributions.

## Skills Required
- SQL fundamentals (SELECT, JOIN, GROUP BY)
- Data aggregation and ranking with `ROW_NUMBER()`
- Analytical thinking to derive insights from relational data

## Usage
1. Load the notebook (`notebook.ipynb`) in Jupyter.
2. Connect to your SQL environment or database containing the tables:
   - `assignments`
   - `donations`
   - `donors`
3. Run each cell step-by-step to execute the queries.
4. Review the outputs to identify top-performing assignments and donor trends.

## Example Output
- Top 5 assignments with the highest donation totals  
- Regional leaders by impact score  
- Summary tables of donor engagement across regions  
