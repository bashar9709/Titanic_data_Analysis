# Titanic_data_Analysis

# Titanic Data Analysis

This project analyzes the Titanic dataset using Python libraries like Pandas, Matplotlib, and Seaborn. The goal is to explore the data, clean it, and visualize important patterns such as survival rates, age distribution, and fare relationships.

## Dataset

The dataset is sourced from [Data Science Dojo on GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv).

## Tools Used

- **Pandas**: For data manipulation and analysis
- **Matplotlib**: For basic plotting
- **Seaborn**: For advanced and aesthetically pleasing data visualization

## Key Steps

1. **Load and Inspect Data**  
   - Loaded the dataset from a URL
   - Displayed info and statistical summary

2. **Data Cleaning**  
   - Filled missing values in the "Age" column with the median
   - Filled missing values in the "Embarked" column with the mode
   - Removed duplicate rows

3. **Data Filtering**  
   - Extracted and displayed data for first-class passengers

4. **Visualizations**  
   - **Bar Chart**: Survival rate by passenger class  
   - **Histogram**: Distribution of passenger ages  
   - **Scatter Plot**: Relationship between age and fare

## Sample Output

- Clear plots showing how survival rates vary by class
- Insights into age distribution of passengers
- Observations about age vs fare patterns

## How to Run

1. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn


