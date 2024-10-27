# Homicide Analysis Project

## Project Overview
This project analyzes homicide rates across various countries and regions using a dataset of homicide counts and rates from different years. The analysis covers trends over time, regional comparisons, and country-specific insights. This project uses Python libraries like Pandas, Matplotlib, and Seaborn to explore, visualize, and present findings on homicide patterns worldwide.

## Dataset
- **File**: `homicide_by_countries.csv`
- **Content**: Contains data on homicide counts and rates by location (country), region, subregion, and year.

### Key Columns:
- **Location**: The country name.
- **Region**: The geographic region.
- **Subregion**: More specific regional classification.
- **Year**: The year the data was recorded.
- **Count**: Total homicide count for the given location and year.
- **Rate**: Homicide rate per 100,000 inhabitants.

## Project Structure

### Data Processing
1. **Data Cleaning**: 
   - Checked for and handled missing values.
   - Converted key columns (`Rate`, `Count`, `Year`) to integer types for accurate analysis.

2. **Data Sorting**:
   - Sorted data by `Count` to identify top countries in homicide counts.

3. **Grouping and Aggregating**:
   - Grouped data by `Region` and `Subregion` to analyze regional trends.
   - Summed counts by year to analyze yearly trends.

### Visualizations
1. **Top 5 Countries by Homicide Count**:
   - A pie chart shows the countries with the highest homicide counts to provide a quick view of the most affected locations.

2. **Total Homicide Counts by Region**:
   - A bar chart displays total homicide counts across different regions, offering insights into regional patterns.

3. **Total Homicide Counts by Subregion**:
   - A bar chart displays homicide counts by subregion for a more detailed regional breakdown.

4. **Yearly Trends in Asia and Europe**:
   - A line chart compares homicide counts over time for Asia and Europe to observe recent trends.

5. **Yearly Sum of Homicide Rates**:
   - A bar chart shows the total homicide rate by year, useful for identifying trends over time globally.

6. **Yearly Sum Count per Region**:
   - A bar chart compares homicide counts per region over time, highlighting regional trends in homicide activity.

## Code Structure
- **Libraries Used**:
  - `pandas` for data manipulation.
  - `matplotlib` and `seaborn` for data visualization.

### Notebook Outline
1. **Data Loading and Initial Exploration**
2. **Data Cleaning and Type Conversion**
3. **Exploratory Analysis**:
   - Sorting, grouping, and aggregating data by various dimensions.
4. **Visualizations**:
   - Pie charts, bar charts, and line charts for in-depth analysis.

## Getting Started
1. **Install Requirements**:
   - Ensure you have Python and the following libraries installed:
     ```bash
     pip install pandas matplotlib seaborn
     ```
2. **Run the Analysis**:
   - Load the dataset (`homicide_by_countries.csv`) in the Jupyter notebook.
   - Follow the analysis steps in the notebook to reproduce the visualizations and insights.

## Insights and Conclusion
- **Regional Comparisons**: Highlights which regions have higher homicide counts.
- **Temporal Trends**: Provides a view of how homicide counts and rates change over time.
- **Country-Specific Insights**: Identifies countries with particularly high homicide rates.

This project gives a comprehensive look at homicide data trends, focusing on regional and temporal patterns. It serves as a portfolio piece showcasing data analysis and visualization skills.

