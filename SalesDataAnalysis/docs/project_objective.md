# Sales Data Analysis Instructions

This data project has been used as a take-home assignment in the recruitment process for the data science positions at 23andMe.

## Assignment

1. Plot daily sales for all 50 weeks.
2. Identify the date on which a sudden change in daily sales occurred.
3. Determine if the change in daily sales on the identified date is statistically significant. Calculate the p-value if it is.
4. Examine whether the data suggests that the change in daily sales is due to a shift in the proportion of male-vs-female customers. Use plots to support your answer; a rigorous statistical analysis is not necessary.

## Daypart Analysis

Assume a given day is divided into four dayparts:

- Night (12:00 AM - 6:00 AM)
- Morning (6:00 AM - 12:00 PM)
- Afternoon (12:00 PM - 6:00 PM)
- Evening (6:00 PM - 12:00 AM)

5. Calculate the percentage of sales in each daypart over all 50 weeks.

## Data Description

The datasets/ directory contains fifty CSV files (one per week) of timestamped sales data. Each row in a file has two columns:

- sale_time - The timestamp on which the sale was made, e.g., 2012-10-01 01:42:22
- purchaser_gender - The gender of the person who purchased (male or female)

## Practicalities

Please work on the questions in the displayed order. Make sure that the solution reflects your entire thought process - it is more important how the code is structured rather than the final answers. You are expected to spend no more than 1-2 hours solving this project.
