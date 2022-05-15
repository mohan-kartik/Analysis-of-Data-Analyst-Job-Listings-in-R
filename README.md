<h1><p align = "center">Analysis-of-Data-Analyst-Job-Listings-in-R</p></h1>

## Project Objective:
To identify the key employment trends in the analyst job sector and visualize using ggplot2 in R.

## Dataset description:
The dataset consists of more than 2k+ job listing for data analyst positions. It has been scrapped from Glassdoor and gives insights into the various job details like salary range, top companies, sectors, etc.

[Link](https://www.kaggle.com/datasets/andrewmvd/data-analyst-jobs)

## Data Processing 
1. Check missing value -  Represented by '-1' & 'Unknown'. <br>
2. String Manipulation -  Remove integer value from column `Company Name`. <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-  Remove characters from column `Job Title`. <br>
3. Feature engineering - Transform `Salary Estimate` column to `Min Salary` and `Max Salary` based on their salary range. <br>

## EDA:
1. Job distribution w.r.t. Ownership
2. Job distribution w.r.t. Sector
3. Distribution of Employee Size
4. Distribution of Minimum Salary
5. Distribution of Maximum Salary
6. Ratings vs Sectors
7. Average Salary vs Ownership

All the visualizations can be see in this [Poster](https://github.com/mohan-kartik/Analysis-of-Data-Analyst-Job-Listings-in-R/blob/main/Miniposter.pdf).
