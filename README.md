# Test Task: Data Analysis and Log Merging
This repository contains the solution to a test task that involves analyzing data from the `task_history.csv` file and merging two JSONL logs.

## Task Description
### Part 1: Data Analysis using Pandas
The file `task_history.csv` contains historical data from a build system. Each record in the history describes a single run of a task `build_name` on a worker machine `worker`.

#### Tasks:
1. **Top 3 Users by Machine Hours Consumption per Week:**
   - For each week, calculate the top 3 users who consumed the most machine hours
   - Calculate the percentage of resources consumed by the top 3 users relative to the total consumption
   - Output the result in the specified format

2. **Daily Machine Time Consumption by Project:**
   - Display a graph showing the daily machine time consumption for each project

3. **Analysis of the Load Spike in the Second Week:**
   - Analyze the weekly total resource consumption
   - Determine the cause of anomalies

### Part 2: Log Merging in Python
Write a function that merges two log files into a single new file without using library functions. The messages in the resulting file must be sorted in ascending order by the timestamp field.

## Solution
### Part 1: Data Analysis
The solution to the data analysis task is located in the `data_analysis_and_log_merging.ipynb` file:
- Data is loaded from `task_history.csv`
- Calculations are performed to determine the top 3 users by machine hours consumption per week
- A graph of daily machine time consumption by project is plotted
- An analysis of the load spike in the second week is conducted

### Part 2: Log Merging
The solution to the log merging task is located in the same file.

To generate logs, run the following command:

`python log_generator.py <path/to/dir>`
