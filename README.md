
<h1 align="center">
<p align="center">  The Ultimate Pandas Guide: Simplifying Data Operations
<br>
    <br>
<!-- PROJECT LOGO -->

  <kbd>
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=DDF4CBF9&background=1F25E6D0&center=true&vCenter=true&random=false&width=435&lines=A+Simple+Pandas+DataFrame+CheatSheet" alt="Typing SVG" /></a>
  </kbd>
  <p align='center'>
    <a href='https://github.com/Data-Portofolio/Analyzing-eCommerce-Business-Performance-with-SQL'>
        <img alt='total stars' title='Total stars on This Project' src='https://custom-icon-badges.herokuapp.com/badge/dynamic/json?logo=star&color=5&labelColor=488207&label=Stars&style=for-the-badge&query=%24.stars&url=https://api.github-star-counter.workers.dev/user/Data-Portofolio'/>
     <a href='https://github.com/astutir'>
        <img alt='Follow Me on GitHub' title='Follow Me on GitHub' src='https://custom-icon-badges.herokuapp.com/github/followers/astutir?style=for-the-badge&&label=GitHub&logo=Github&color=pink'/>
    <a href='https://www.linkedin.com/in/a-rahmawati' target='_blank'>
        <img src='https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white'/>
    <a href='mailto:astutirahmarubi@gmail.com' target='_blank'>
        <img src='https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white'/>
 </p>

 </h1>

Welcome to My repository! This comprehensive guide serves as your key to mastering the powerful Pandas library, simplifying data operations, and unleashing the full potential of your data analysis tasks.

**About This Guide:**

Pandas is a go-to library for data manipulation, analysis, and transformation. However, its rich set of functions can be intimidating for beginners. This guide is designed to make your journey with Pandas both accessible and enjoyable. It offers a hands-on approach, packed with practical tips, tricks, and real-world examples to help you become proficient in using Pandas for a wide range of tasks.

**Read and Write Data:**
=========================

1. **pd.read_csv()**: Explore the world of data with ease! Read data from a CSV file and convert it into a DataFrame.
2. **pd.read_excel()**: Bring the world of spreadsheets into your DataFrame with pd.read_excel().
3. **df.to_csv()**: Save your analysis results back to a shareable CSV format.
4. **df.to_excel()**: Showcase your hard work in a neatly formatted Excel file.
5. **df.to_sql()**: Let Pandas assist you in saving your DataFrame to your SQL database.

**Info and Statistics:**
=========================

6. **df.info()**: Hand over control to Pandas to provide a comprehensive summary of your DataFrame's structure.
7. **df.head()**: Take a sneak peek at your initial data to gain a quick understanding.
8. **df.tail()**: Scroll through the tail end of your data to inspect the outcomes.
9. **df.describe()**: Display statistical prowess with pd.describe() and uncover all the details.
10. **df.shape**: Observe your DataFrame's dimensions, how many rows and columns it has.
11. **df.columns**: Create a list of column names in the blink of an eye.
12. **df.dtypes**: Use dtypes to reveal the secrets of column data types.
13. **df.isnull()**: Let Pandas unveil the places where your data is missing.

**Data Selection:**
=========================
14. **df['column']**: Pick and extract the necessary column from the DataFrame.
15. **df[['column1', 'column2']]**: Bundle your data by selecting multiple columns at once.
16. **df.loc[]**: Perform selection based on row and column labels.
17. **df.iloc[]**: Execute selection based on row and column indices.

**Data Manipulation:**
=========================
18. **df.drop()**: Easily remove unwanted columns or rows.
19. **df.rename()**: Personalize your DataFrame by changing column or index names.
20. **df.set_index()**: Give your DataFrame the index that suits you.
21. **df.reset_index()**: Reset the index and reorganize your DataFrame to its original state.
22. **df.sort_values()**: Use sort_values() to arrange data as you desire.

**Aggregation and Grouping:**
=========================
23. **df.groupby()**: Create groups based on specific columns to perform aggregation operations.
24. **df.agg()**: Let Pandas extract the information you need from grouped data.
25. **df.pivot()**: Present your data in a beautiful pivot format.
26. **df.melt()**: Transform data into a long format and discover the pattern.

**Merging and Joining:**
=========================
27. **df.merge()**: Intuitively combine DataFrames with ease.
28. **df.join()**: Merge with another DataFrame to intelligently combine information.
29. **pd.concat()**: Powerfully combine multiple DataFrames into one.

**Data Filling and Replacement:**
=========================
30. **df.fillna()**: Fill missing values with policies you define.
31. **df.replace(to_replace, value)**: Replace values with new ones as per your requirements.

**String Operations (on string-type columns):**
=========================
32. **df['column'].str.upper()**: Elevate all letters to uppercase!
33. **df['column'].str.contains()**: Unearth patterns in text with df['column'].str.contains().
34. **df['column'].str.title()**: Capitalize the first letter of each word in the string.
35. **df['column'].str.capitalize()**: Capitalize the first letter of the string.
36. **df['column'].str.swapcase()**: Swap the case of each character (e.g., "aBc" becomes "AbC").
37. **df['column'].str.strip()**: Remove leading and trailing whitespace.
38. **df['column'].str.lstrip()**: Remove leading whitespace.
39. **df['column'].str.rstrip()**: Remove trailing whitespace.
40. **df['column'].str.strip('char')**: Remove specific characters from the start and end.
41. **df['column'].str.lstrip('char')**: Remove specific characters from the start.
42. **df['column'].str.rstrip('char')**: Remove specific characters from the end.
43. **df['column'].str.len()**: Calculate the length (number of characters) of each string.
44. **df['column'].str.slice(start, stop)**: Extract a substring based on the specified start and stop positions.
45. **df['column'].str.replace(old, new)**: Replace a substring with a new value.
46. **df['column'].str.replace(r'pattern', new)**: Replace substrings based on a regular expression pattern.
47. **df['column'].str.contains('substring')**: Check if a string contains a specific substring and returns a boolean.
48. **df['column'].str.startswith('prefix')**: Check if a string starts with a specific prefix and returns a boolean.
49. **df['column'].str.endswith('suffix')**: Check if a string ends with a specific suffix and returns a boolean.
50. **df['column'].str.split('delimiter')**: Split a string into a list of substrings based on a delimiter.
51. **df['column'].str.join('separator')**: Join a list of strings with a specified separator.
52. **df['column'].str.cat(sep='separator')**: Concatenate strings within a column, separated by a specified separator.

**Datetime Operations (on datetime-type columns):**
=========================
53. **df['column'].dt.year**: Peek at the year effortlessly from a datetime column.
54. **df['column'].dt.month**: Dip your fingers to unearth the month from datetime data.
55. **df['column'].dt.day**: Extracts the day component from the datetime column.
56. **df['column'].dt.hour**: Extracts the hour component from the datetime column.
57. **df['column'].dt.minute**: Extracts the minute component from the datetime column.
58. **df['column'].dt.second**: Extracts the second component from the datetime column.
59. **df['column'].dt.microsecond**: Extracts the microsecond component from the datetime column.
60. **df['column'].dt.date**: Extracts the date component (without the time) from the datetime column.
61. **df['column'].dt.time**: Extracts the time component (without the date) from the datetime column.
62. **df['column'].dt.dayofweek**: Returns the day of the week as an integer, where Monday is 0 and Sunday is 6.
63. **df['column'].dt.day_name()**: Returns the day of the week as a string (e.g., 'Monday', 'Tuesday').
64. **df['column'].dt.is_month_start**: Returns a Boolean indicating if the date is the start of the month.
65. **df['column'].dt.is_month_end**: Returns a Boolean indicating if the date is the end of the month.
66. **df['column'].dt.is_year_start**: Returns a Boolean indicating if the date is the start of the year.
67. **df['column'].dt.is_year_end**: Returns a Boolean indicating if the date is the end of the year.
68. **df['column'].dt.dayofyear**: Returns the day of the year as an integer.
69. **df['column'].dt.week**: Returns the week number of the year.
70. **df['column'].dt.weekday**: Returns the day of the week as an integer, where Monday is 0 and Sunday is 6.
71. **df['column'].dt.quarter**: Returns the quarter of the year as an integer (1-4).
72. **df['column'].dt.to_period('M')**: Converts the datetime to a period with a specified frequency (e.g., 'M' for monthly).
73. **df['column'].dt.to_period('D')**: Converts the datetime to a period with a daily frequency.
74. **df['column'].dt.strftime('format_string')**: Allows you to format the datetime as a string using a custom format.

### Example 1:

```python
import pandas as pd

# Sample DataFrame with datetime data
data = {
    'date_column': ['2023-01-01', '2023-02-15', '2023-03-20', '2023-04-10'],
    'value': [100, 150, 200, 250]
}
df = pd.DataFrame(data)

# Example 1: Date Parsing and Conversion
df['date_column'] = pd.to_datetime(df['date_column'])

# Example 2: Date Extraction
df['year'] = df['date_column'].dt.year
df['month'] = df['date_column'].dt.month
df['day'] = df['date_column'].dt.day

# Example 3: Resampling (Monthly Sum)
monthly_data = df.set_index('date_column').resample('M').sum()

# Example 4: Time Difference Calculation
df['days_since_event'] = (df['date_column'] - pd.to_datetime('2023-01-01')).dt.days

# Example 5: Date Range Generation
date_range = pd.date_range(start='2023-01-01', end='2023-12-31', freq='D')

# Example 6: Offset by 10 days
df['date_column_offset_10_days'] = df['date_column'] + pd.DateOffset(days=10)

# Example 7: Offset by 2 months
df['date_column_offset_2_months'] = df['date_column'] + pd.DateOffset(months=2)

```
### Example 2
```python
import pandas as pd

# Sample DataFrame with datetime data
data = {
    'date_column': ['2023-01-01', '2023-02-15', '2023-03-20', '2023-04-10'],
}
df = pd.DataFrame(data)
df['date_column'] = pd.to_datetime(df['date_column'])

# Extract the day of the week (0 = Monday, 6 = Sunday)
df['day_of_week'] = df['date_column'].dt.dayofweek

# Filter for weekdays (Monday to Friday, day_of_week 0 to 4)
weekdays_df = df[df['day_of_week'].isin([0, 1, 2, 3, 4])]

# Filter for weekends (Saturday and Sunday, day_of_week 5 and 6)
weekends_df = df[df['day_of_week'].isin([5, 6])]

# Print the results
print("Weekdays:")
print(weekdays_df)
print("\nWeekends:")
print(weekends_df)

```

**Converting Column Data Types in Pandas**
===========================
- `df['column_name'] = df['column_name'].astype('int64')`
- `df['date_column'] = pd.to_datetime(df['date_column'])`
- `df['category_column'] = df['category_column'].astype('category')`
- `df['numeric_column'] = pd.to_numeric(df['numeric_column'], errors='coerce')`
- `df['boolean_column'] = df['boolean_column'].astype(bool)`
- `df['string_column'] = df['string_column'].astype(str)`
