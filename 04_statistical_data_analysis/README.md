# Project Title:
## Project Description
## Project Structure
## Results
## Technologies Used
## Future Work
## Acknowledgments

# Project Title: Megaline Tariff Analysis



## Project Description
As an analyst at "Megaline," a nationwide mobile carrier, your task is to conduct a preliminary analysis of two of the company's tariff plans: "Smart" and "Ultra." The commercial department wants to understand which tariff plan is more profitable. You have data for 500 Megaline users, including details about their location, tariff usage, and behavior throughout the year 2018. Your goal is to analyze customer behavior and determine which tariff plan is better.



## Project Structure

1. Data Exploration
Load and explore the dataset from the following files:
calls.csv: Information about calls.
internet.csv: Information about internet sessions.
messages.csv: Information about messages.
tariffs.csv: Tariff details.
users.csv: User information.
Inspect the first few rows, get basic info, and visualize distributions.

2. Data Preprocessing
Convert date columns (reg_date, churn_date, call_date, message_date, session_date) to datetime format.
Address calls with zero duration; these are not errors but missed calls.
Correct fractional values in the duration column.
Remove the 'Unnamed: 0' column from the sessions DataFrame.
Create a month column in the calls, messages, and sessions DataFrames.

3. Data Analysis
Calculate monthly usage for each user:
Number of calls and minutes (calls_per_month, minutes_per_month).
Number of messages (messages_per_month).
Data usage in megabytes (sessions_per_month).
Analyze the data to understand customer behavior.
Hypothesis Testing

4. Test two hypotheses with a significance level (alpha) of 0.05 (5%):
Hypothesis 1: Check if the average revenue from users on the "Ultra" and "Smart" tariffs differs.
Hypothesis 2: Check if the average revenue from users in Moscow differs from users in other regions.



## Results
The project will provide insights into customer behavior and the profitability of Megaline's tariff plans. It will also confirm or reject hypotheses related to revenue differences between tariff plans and regions.

## Technologies Used
Python
Pandas
NumPy
Matplotlib
SciPy
Jupyter Notebook



## Future Work
In future iterations of this project, more advanced statistical analysis and predictive modeling can be applied to forecast revenue trends. Additionally, machine learning models can be developed to predict customer behavior and tailor marketing strategies.

## Acknowledgments
Data provided by Yandex Practicum.