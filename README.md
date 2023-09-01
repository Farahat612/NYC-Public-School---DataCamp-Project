# Analyzing NYC Public School Test Result Scores
Using summary statistics and filters to analyze test scores across New York City's public schools!, A DataCamp project.


## Project Overview

The "Analyzing NYC Public School Test Result Scores" project involves exploring and analyzing test performance data from public schools in New York City (NYC). This project aims to provide insights into school performance across different boroughs, identify schools with outstanding SAT scores, and address data quality issues.

## Project Description

Every year, American high school students take SATs, standardized tests that play a significant role in the college admissions process. In this project, we work with a SQL database containing data on SAT performance across NYC public schools. The database consists of a single table named "schools" with various columns, including school name, borough, building code, average math, reading, and writing scores, and the percentage of students completing SATs.

### Project Tasks

1. **Inspecting the Data**: We begin by inspecting the first 10 rows of the database to familiarize ourselves with the data.

2. **Finding Missing Values**: We identify schools that did not report the percentage of students tested and calculate the total number of schools in the database.

3. **Schools by Building Code**: We determine the number of unique school locations based on building codes.

4. **Best Schools for Math**: We identify schools with an average math score of at least 80% and rank them.

5. **Lowest Reading Score**: We find the lowest average reading score among all schools.

6. **Best Writing School**: We identify the school with the highest average writing score.

7. **Top 10 Schools**: We determine the top 10 schools based on the total SAT scores (math, reading, and writing).

8. **Ranking Boroughs**: We analyze school performance by NYC borough, calculating the number of schools and average SAT scores per borough.

9. **Brooklyn Numbers**: We focus on Brooklyn, finding the top five schools for math performance.

## Repository Content

- `datasets` directory containing the SQL script `createdb.sql` and the modified CSV file `schools_modified.csv`.
- `notebook-before.ipynb`: Jupyter Notebook file containing code before execution.
- `notebook-after.ipynb`: Jupyter Notebook file containing code after execution.

## Project Instructions

Each task in the project corresponds to a specific analysis or query. The provided SQL database and Jupyter Notebook files (`notebook-before.ipynb` and `notebook-after.ipynb`) contain the code and queries for each task. You can run these notebooks to see the analysis results.

## No Limitations or Issues

As of the project's completion, there are no known limitations or issues. The data analysis tasks have been designed to provide valuable insights into NYC public school test performance.

## License

This project is provided under the [MIT License](LICENSE.md), allowing you to use, modify, and distribute the code and resources as per the terms of the MIT License.

---

Explore the project's components and run the provided Jupyter Notebooks to delve into the analysis of NYC public school SAT scores. For more details, refer to the notebooks and the dataset in the `datasets` directory.
