# NYC Public Schools SAT Performance Analysis

## Project Overview
This project analyzes the SAT performance of public schools across New York City's five boroughs. The goal was to identify top-performing schools in mathematics and understand the variability in scores across different geographic areas.

## Key Questions Answered
1. **Best Math Results:** Which schools have average math scores of at least 80% (640/800)?
2. **Top 10 Schools:** What are the top 10 schools based on combined SAT scores (Math + Reading + Writing)?
3. **Borough Variation:** Which borough shows the largest standard deviation in total SAT scores?

## Technologies Used
* **Python**
* **Pandas**: Used for data manipulation, filtering, and aggregation.
* **Jupyter Notebook**: For interactive data exploration.

## Analysis Summary
* **Math Excellence:** Identified schools that met the 80% threshold for mathematics excellence.
* **Total Performance:** Calculated a new `total_SAT` metric to rank schools globally.
* **Statistical Insights:** Grouped data by `borough` to calculate the count of schools, average SAT scores, and standard deviation to find where student performance varies the most.

## Dataset
The analysis uses the `schools.csv` dataset, which contains school names, borough locations, and average scores for the three SAT sections.
