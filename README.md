# Hands-On Assignment 1

## Problem Statement

You are tasked with analyzing the Bitly data from the USA.gov website to explore user behavior based on the time zones from which the links were accessed.

## Objectives

1. Load the Bitly data from a provided text file.
2. Clean the data to handle missing values and ensure accuracy.
3. Reshape the data to analyze frequency across different time zones.
4. Create a summary table that presents the cleaned and aggregated data.

## Expected Output

1. A cleaned DataFrame with relevant columns for analysis.
2. A summary table showing the count of accesses per time zone.
3. A cleaned and reshaped DataFrame that is ready for further analysis.

## Instructions

1. **Data Loading**
   - Use `pandas` to load the data from `bitly_data.txt`.
   - Parse the JSON records into a DataFrame.

2. **Data Cleaning**
   - Identify and handle missing values in the `tz` (time zone) column.
   - Remove any records without a time zone.
   - Standardize the time zone names (e.g., replace empty strings with "Unknown").

3. **Data Wrangling**
   - Create a summary table that counts the frequency of each time zone.
   - Reshape the data, if necessary, to facilitate analysis.
   - Use the `groupby` method to aggregate counts by time zone.

4. **Documentation**
   - Comment your code to explain each step.
   - Include any assumptions you made during your analysis.