# 🏅 Olympic Games Data Analysis

## Overview

This project analyzes historical Olympic Games data using Python,
Pandas, and data visualization techniques.

The goal of this project is to identify trends in Olympic participation,
medal performance, sports, countries, and hosting patterns.

## Questions

- On average, does the host country win more medals than the non-host countries?
- Do rich countries win more medals than poor countries?
- How does height, weight, and age affect athletes' results?

## Technologies

- Python
- Pandas
- Sqldf 
- Jupyter Notebook

## Dataset

The project uses historical Olympic Games data containing information
about athletes, countries, sports, events, and medals.

Additional datasets are used to map NOC codes to countries and
identify Olympic host countries with the host year.

## Analysis

The analysis includes:

- Exploratory data analysis
- Grouping and aggregation
- Statistical analysis
- Data visualization

## Key Findings

### Finding 1
I created olympic_hosts.csv because I wanted to compare the performance of host countries with non-host countries for each year and it made querying the data easier. 
On average, the host countries won 71 medals while the non-host countries won 5.4 medals per year.

### Finding 2
I wrote down every advanced economy's three-letter code from this website: (https://www.imf.org/en/publications/weo/weo-database/2023/april/groups-and-aggregates).
Then, I wrote a case statement to make a column to label each country as rich or poor. I focused on results from 1992 and later because using results before would get complicated with countries like the Soviet Union and Yugoslavia. On average, the rich countries won 21.34 medals while the poor countries won 4.07 medals.

### Finding 3
I made scatter plots and used the LinearRegression function. I found the correlation between height and weight was high for all athletes, while the other factors had almost no correlation.

## How to Run

Clone the repository:

```bash
git clone https://github.com/odhayaa/olympic-data-analysis.git