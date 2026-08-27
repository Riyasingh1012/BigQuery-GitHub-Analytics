# BigQuery GitHub Analytics

## Project Overview
Analyzed GitHub public dataset using Google BigQuery SQL to extract insights 
about programming languages, repositories, and file types.

## Datasets

### 1. github_languages.csv
- **Query:** Top 10 programming languages by usage
- **Columns:** language, count
- **Insights:** Python, JavaScript, C are most popular

### 2. repository_stats.csv
- **Query:** Number of files per repository
- **Columns:** repo_name, file_count
- **Insights:** cdnjs/cdnjs has 14M+ files (largest)

### 3. file_extensions.csv
- **Query:** Most common file types in repositories
- **Columns:** file_extension, file_count
- **Insights:** .README.md, .png, .json are most common

## Tools Used
- Google BigQuery (SQL queries)
- Google Cloud Platform
- CSV export

## SQL Queries
All queries available in queries.sql file
