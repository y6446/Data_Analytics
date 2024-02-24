# Bikes Peak Hour and Stations - Data I/O Hackathon

# 02/24/2024

# Yousef Alshanqiti & Mark Wang

This Python program analyzes peak bike hours usage and stations based on a dataset of bike records. It performs the following tasks:

1. **Data Preparation:**
    - Reads delivery data from 12 separate CSV files into individual DataFrames.
    - Concatenates the DataFrames into a single DataFrame.
    - Extracts the hour from the `started_at` and `ended_at` columns.
    - Calculates the delivery duration in hours.
    - Drops any rows with missing values.

2. **Most Frequent Hour Analysis:**
    - Determines the hour with the most frequent bike starts.
    - Formats the hour in 12-hour format with AM/PM indicator.

3. **Most Frequent Station Analysis:**
    - Finds the station with the most frequent bikes starts.

4. **Report Generation:**
    - Creates an HTML page that summarizes the analysis results.
    - Includes the most frequent hour, and most frequent station information.
    - Embeds the bar chart image in the HTML page.
    - Saves the HTML page to a file and displays it in the notebook.

This program provides valuable insights into the busiest bikes hours and the most popular station for bikes. The generated report can be used for planning delivery schedules, resource allocation, and identifying peak demand patterns.
