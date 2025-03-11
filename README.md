# -Employee-Salary-Analysis_202401100300
# Employee Data Analysis

## Overview
This script analyzes employee data from a CSV file (`employee_data.csv`). It performs various statistical analyses and visualizations to gain insights into employee salary distribution, department-wise statistics, experience correlations, and outlier detection.

## Requirements
Ensure you have the following Python libraries installed before running the script:

```bash
pip install pandas matplotlib seaborn
```

## Features
1. **Basic Information & Preview:**
   - Displays dataset info (column names, data types, missing values, etc.)
   - Shows the first few rows of the dataset

2. **Summary Statistics:**
   - Computes summary statistics (mean, median, standard deviation, etc.)

3. **Department-wise Analysis:**
   - Calculates the average salary and experience per department
   - Counts employees in each department

4. **Correlation Analysis:**
   - Computes correlation between Experience and Salary

5. **Highest & Lowest Salary Employees:**
   - Identifies employees with the highest and lowest salaries

6. **Outlier Detection:**
   - Detects salary outliers using the Interquartile Range (IQR) method

7. **Data Visualization:**
   - Histogram of salary distribution
   - Scatter plot of Experience vs Salary (colored by department)
   - Boxplot of Salary by Department
   - Trendline for Salary Growth with Experience
   - Pie chart of department-wise employee distribution

## How to Use
1. Place your `employee_data.csv` file in the same directory as the script.
2. Run the script using Python:
   
   ```bash
   python script_name.py
   ```
3. The script will print analysis results and display graphs for visualization.

## Expected CSV Format
Ensure the `employee_data.csv` file follows this format:

| EmployeeID | Name    | Department | Salary | Experience |
|------------|--------|------------|--------|------------|
| 101        | Alice   | HR         | 50000  | 5          |
| 102        | Bob     | IT         | 70000  | 7          |
| ...        | ...     | ...        | ...    | ...        |

## Output
The script provides:
- Text-based insights in the console
- Graphical representations of salary trends and distributions

## Notes
- Modify `file_path` if the CSV file is located elsewhere.
- Adjust visualization settings (e.g., colors, figure sizes) as needed.

## License
This project is open-source. Feel free to modify and use it as needed!

