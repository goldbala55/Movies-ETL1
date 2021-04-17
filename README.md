# Movies-ETL1
Extracting, cleaning and merging Movie data from Wiki, Kaggle (MovieLens ratings, TMDb metadata) and loading it to a PostgreSQL DB.
## Project Overview
The project goal is to:
1. Extract Movie metadata (titles, directors, budgets, and more) from publicly available sites.
2. Inspect and transform the data using a myriad of techniques.
   1. This standardizes and presents the data in a uniform manner for easy analysis.
3. Consolidate/merge the transformed data and load into PostgreSQL DB tables.

## Resources
1. Wikipedia movie data provided as a JSON file.
2. GroupLens data - Kaggle.com provides:
   1. The MovieLens ratings data (csv)
   2. TMDb movie metadata (csv)
3. Software: Python 3.7.9, Jupyter Notebook 6.1.4, pandas 1.1.3, matplotlib 3.3.2, numpy 1.17.0, regex 2020.10.15
   1. Git Bash 4.4.23, git LFS 2.13.2
   2. PostgreSQL 13, psycopg2 2.8.5, sqlalchemy 1.3.20
