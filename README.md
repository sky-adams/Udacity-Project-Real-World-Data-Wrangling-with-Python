# Udacity-Project-Real-World-Data-Wrangling-with-Python

## Description

I completed this project as part of Udacity's Data Analyst nanodegree program. The project uses data from the Audubon Society's annual Christmas Bird Count in Santa Barbara, California, as well as historical rainfall data for Santa Barbara. After wrangling the data and merging the datasets, I analyzed it to look at trends in bird populations in Santa Barbara over time and explored whether or not there is a correlation between annual rainfall and the size of bird populations.

## Motivation
Data collected from real-world sources is often messy, inconsistent, or incomplete, which can significantly hinder effective analysis. This project focuses on applying data wrangling techniques to clean, transform, and integrate two key environmental datasets—bird population counts and rainfall measurements in Santa Barbara. By making these datasets more analyzable, the goal is to uncover meaningful patterns in bird populations over time and explore how rainfall may influence bird populations. This analysis generates insights relevant to conservation and climate impact studies.

## Project Scope and Deliverables
* Gathered two datasets using different methods: downloading CSV and programmatic Excel file download.
* Assessed data quality and tidiness issues programmatically and visually.
* Cleaned datasets, resolving missing data, incorrect types, and inconsistent formatting, and combined them.
* Analyzed and visualized cleaned data to examine trends and correlations.

## Key Findings
* There was a significant decline in the number of birds counted per party hour (the total number of birds observed divided by the total hours spent by all birding parties during the count, a proxy for the bird population) in the 60s and 70s. From 1980 onwards there was an overall decline, but with periods of increases.
*  There isn't a clear overall increase or decrease in rainfall over time, but the variance in annual rainfall has increased over time.
*  There isn't a strong correlation between total annual rainfall and the number of birds counted per party hour.

## Data
The Christmas Bird Count data is not included in the repository as that would not be in line with the Audubon Society's [Terms of Use](https://www.audubon.org/content/policy-regarding-use-christmas-bird-count-data) for the data. However, it may be downloaded from the Audubon Society's [Christmas Bird Count data website](https://netapp.audubon.org/CBCObservation/Historical/ResultsByCount.aspx#). A detailed description of the data that I downloaded is in the Jupyter Notebook in this repository.

The historical rainfall data is available for download from the County of Santa Barbara's website ([link to file](https://files.countyofsb.org/pwd/hydrology/historic%20data/rainfall/XLS%20Dailys/234dailys.xls)).

## File
Data_Wrangling_project.ipynb: Contains all the code for the project as well as explanations of the process and results, including visuals.

## Usage
1. Clone or download this repository.
2. Create a folder named "data" in the repo, then download and save into it the Christmas bird count data for Santa Barbara from the site linked above.
3. Create a folder named "results" where the cleaned data will be stored.
4. Ensure the necessary Python packages are installed (pandas, numpy, requests, os).
5. Run the Jupyter notebook to reproduce the data wrangling and analysis.
6. Examine visualizations and summary outputs to understand insights.
