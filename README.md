# Weather-BigData-Analysis-Python-Project
This project demonstrates a comprehensive analysis of weather data using Python, focusing on various key data science concepts. The project showcases how to manipulate and analyze big datasets using Python's powerful data analysis libraries.

# Data Analysis with Python | Weather Dataset

This project demonstrates a comprehensive analysis of weather data using Python, focusing on various key data science concepts. The project showcases how to manipulate and analyze big datasets using Python's powerful data analysis libraries.

## Project Overview

In this project, we perform a detailed analysis of a weather dataset to extract meaningful insights. The dataset contains various attributes related to weather conditions, such as temperature, wind speed, visibility, humidity, etc. Using Python's pandas library, we explore the dataset, perform data cleaning, and answer several important questions.

### Commands Used

Here are some of the key pandas commands used in this project:

- head(): Displays the first N rows in the dataset (default is N=5).
- shape: Provides the total number of rows and columns in the dataframe.
- index: Returns the index (row labels) of the dataframe.
- columns: Lists all column names in the dataframe.
- dtypes: Displays the data type of each column.
- unique(): Shows all unique values in a specific column.
- nunique(): Returns the count of unique values in a column.
- count(): Displays the number of non-null values in each column.
- value_counts(): Shows unique values in a column along with their counts.
- info(): Provides a summary of the dataframe, including the number of non-null entries, column types, and memory usage.

### Questions Answered

Here are the specific questions we address in the analysis:

1. Find all the unique 'Wind Speed' values in the data.
2. Find the number of times when the 'Weather is exactly Clear'.
3. Find the number of times when the 'Wind Speed was exactly 4 km/h'.
4. Identify all the null values in the data.
5. Rename the column name 'Weather' to 'Weather Condition'.
6. Calculate the mean 'Visibility'.
7. Determine the standard deviation of 'Pressure'.
8. Calculate the variance of 'Relative Humidity'.
9. Find all instances when 'Snow' was recorded.
10. Find all instances when 'Wind Speed is above 24 km/h' and 'Visibility is 25 km'.
11. Compute the mean value of each column for each 'Weather Condition'.
12. Find the minimum and maximum values of each column for each 'Weather Condition'.
13. Show all records where the 'Weather Condition' is Fog.
14. Find all instances when 'Weather is Clear' or 'Visibility is above 40'.
15. Find all instances where:
    - 'Weather is Clear' and 'Relative Humidity is greater than 50', or
    - 'Visibility is above 40'.

## How to Run the Project

1. Install Required Libraries: Ensure you have Python installed, along with the pandas library. You can install pandas using pip:

   ```sh
   pip install pandas
   ```

2. Load the Dataset: Download the weather dataset and load it into a pandas dataframe.

3. Run the Analysis: Execute the Python script to perform the analysis. The script will utilize the aforementioned commands to explore the dataset and answer the listed questions.

4. View Results: The results of the analysis will be printed to the console, providing insights into various weather conditions and patterns.

## Conclusion

This project is an excellent demonstration of how Python can be used to analyze big datasets, extract valuable information, and present findings in a clear and concise manner. By following the steps outlined in this README, you can replicate the analysis and gain a deeper understanding of the weather data.
