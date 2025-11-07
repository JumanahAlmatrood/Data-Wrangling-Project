# Data Wrangling Project

## Project Overview
This project demonstrates the complete process of data wrangling and analysis using Python.  
The objective of the project is to gather, assess, clean, and analyze movie-related data from two different datasets, and then explore insights that can be extracted after preparing the data properly.

## Datasets
This project uses two datasets:

1. **Movies Metadata Dataset**  
   Contains detailed information about movies including titles, genres, release dates, budget, revenue, overview, and ratings.

2. **Netflix Titles Dataset**  
   Contains information about movies and series available on Netflix such as title, content type, release year, country, and description.

Due to GitHub's file upload size limit, the original datasets are not included directly in this repository.

You can download them from the link below:

- **Dataset Folder (Movies Metadata + Netflix Titles):**  
  https://drive.google.com/drive/folders/1ihX8ISzSUUmwsj1VhcZYjiJOIGlkEWTl?usp=sharing

Make sure the sharing settings for the link are set to:  
**Anyone with the link → Viewer**

## Data Wrangling Steps

### 1. Gathering
- Imported both datasets from CSV files.
- Loaded the datasets into Pandas DataFrames for further processing.

### 2. Assessing
- Conducted visual and programmatic assessment to understand data structure.
- Identified issues such as:
  - Missing values
  - Duplicates
  - Inconsistent date and numeric formats
  - Columns with irrelevant or unusable data

### 3. Cleaning
- Removed duplicate entries.
- Handled missing values by filling or dropping based on context.
- Converted data types (e.g., converting release year to integer).
- Standardized column names where needed.
- Filtered out invalid or incomplete records.
- Merged the two datasets where comparison was needed.

## Analysis and Insights
After cleaning the data, exploratory analysis was performed, which included:

- Comparing movie production trends across years
- Exploring the most frequent genres
- Examining the difference between Netflix content and general movie data
- Observing runtime and popularity patterns

The cleaned dataset enabled reliable conclusions and visual summaries about movie production and streaming trends.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Challenges
- Handling missing and inconsistent data across different sources
- Aligning movie names and shared attributes when merging datasets
- Dealing with irregular text-based fields (genres, descriptions)

## Final Output
The final Jupyter Notebook file contains:
- Code for gathering, assessing, and cleaning data
- Visualizations and summary statistics
- Explanation and reasoning for each transformation done


