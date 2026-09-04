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




## 📊 Interactive Data Studio Dashboard

View the live dashboard here:
**[GitHub Analytics Dashboard](https://datastudio.google.com/reporting/61b80db1-63e1-42a7-9357-ab58113e006a)**

### Dashboard Metrics Overview:
- **Total Repositories Analyzed:** 15
- **Total Unique Languages:** 10
- **Total Files:** 80,620,778
- **Dominant File Type:** README.md (55%)

### Dashboard Visualizations:
- Executive metrics (4 KPI cards)
- File type distribution analysis
- Programming language rankings
- Repository scale metrics

### Key Insights from Dashboard Analysis:

✅ **Shell Scripts Lead:** With 8,539 repositories, shell scripts dominate as the most common language in GitHub, showing the importance of system administration and automation in open-source projects.

✅ **Documentation-Focused Codebase:** README.md files comprise 55% of all files across GitHub, indicating strong documentation practices in the developer community.

✅ **The Giant Repository:** cdnjs/cdnjs is the largest repository with 14M+ files, roughly 5x larger than the next largest repository, making it a central resource for web developers.

✅ **Python & JavaScript Combined:** Python (1,215 repos) and JavaScript (1,081 repos) together represent 20% of language adoption, making them the top modern languages.

### How to View the Dashboard:
1. Click the dashboard link above
2. View live metrics and charts
3. All data refreshes automatically from BigQuery

### Project Files:
- `README.md` - This documentation
- `queries.sql` - SQL queries used (if available)
- `data/github_languages.csv` - Language data
- `data/repository_stats.csv` - Repository metrics
- `data/file_extensions.csv` - File type data
- `dashboard-screenshot.png` - Dashboard preview

---

**Last Updated:** September 4, 2026  
**Data Source:** Google BigQuery (bigquery-public-data.github_repos)  
**Dashboard:** Google Data Studio
