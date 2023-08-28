# Project Title: Real Estate Market Analysis


## Project Description
In this project, you will work with data from the Yandex Real Estate service, which contains a history of property listings for sale in St. Petersburg and neighboring areas over several years. Your task is to perform data preprocessing and explore the dataset to discover interesting features and dependencies that exist in the real estate market.

Each property listing in the dataset contains two types of data: user-added data, such as apartment area, floor, and the number of balconies, and geographic data, including distances to the city center, airport, and nearest park.


## Project Structure

1. Data Exploration
Load the data from the file.
Explore general information about the dataset.
Create histograms for all columns to gain insights.

2. Data Preprocessing
Identify and handle missing values:
Determine which columns have missing values.
Fill missing values where appropriate, e.g., replacing missing balcony counts with 0.
Document reasons for missing values in a markdown cell.
Assess data types in each column:
Identify columns where data type conversion is necessary.
Convert data types in selected columns.
Explain why data type changes are required in a markdown cell.
Handle implicit duplicates in the 'locality_name' column:
Remove or correct duplicate values.
Document the approach used.

3. Feature Engineering
Add new columns with the following parameters:
Price per square meter.
Day of the week the listing was published (0 for Monday, 1 for Tuesday, etc.).
Month of publication.
Year of publication.
Floor type of the apartment (e.g., 'first', 'last', 'other').
Distance to the city center in kilometers (convert from meters and round to integers).

4. Exploratory Data Analysis (EDA
Explore the following property parameters:
Total area.
Living area.
Kitchen area.
Property price.
Number of rooms.
Ceiling height.
Apartment floor.
Floor type.
Total number of floors in the building.
Distance to the city center (in meters and kilometers).
Distance to the nearest airport.
Distance to the nearest park.
Day and month of publication.
Create separate histograms for each parameter and provide observations in a markdown cell.
Analyze the 'days_exposition' parameter to determine the typical time it takes to sell a property.

5. Correlations and Dependencies
Investigate factors affecting the total property price, such as:
Total area.
Living area.
Kitchen area.
Number of rooms.
Floor type.
Publication date (day, month, year).
Create visualizations (e.g., scatter plots, correlation matrices) to show the relationships.
Calculate the average price per square meter in the ten localities with the highest number of listings. Identify the localities with the highest and lowest square meter prices.

6. City Center Analysis
Focus on properties located in St. Petersburg using the 'locality_name' column.
Calculate the average price per kilometer from the city center.
Describe how property prices relate to distance from the city center.

## Results
The results of this analysis will provide valuable insights into the real estate market, including property pricing trends, factors influencing property prices, and the typical time it takes to sell a property. These findings will be summarized in the project's conclusion.



## Technologies Used
Python
Pandas
Matplotlib
Seaborn
Scipy
Jupyter Notebook



## Future Work
This project could be extended to include more advanced statistical modeling and predictive analytics to forecast property prices or estimate the time it takes to sell a property. Additionally, further data collection and analysis could be performed to uncover more intricate patterns in the real estate market.



## Acknowledgments
Data provided by Yandex Practicum.