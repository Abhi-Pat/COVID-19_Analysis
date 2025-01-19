# COVID-19 Data Analysis and Visualization Project

This repository contains an in-depth analysis and visualization of COVID-19 data across different countries. The project leverages various Python libraries such as **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly** to analyze and visualize the data in multiple formats like bar plots, pie charts, tree maps, and time-series visualizations. The focus is on automating repetitive tasks for handling and visualizing COVID-19 data.

### Libraries Used:
- **NumPy**: Used for numerical computations.
- **Pandas**: Used for data manipulation and analysis.
- **Matplotlib**: Used for creating static, animated, and interactive plots.
- **Seaborn**: Built on top of Matplotlib, used for statistical plotting.
- **Plotly**: Used for interactive charts, including pie charts, bar plots, and time-series plots.
- **Plotly Subplots**: Used to create subplots for detailed analysis and visualization.

### Key Steps and Analysis

1. **Data Preparation**:
   - Imported COVID-19 data from **6 CSV files** into **6 separate DataFrames**.
   - Created an automation function to import data, allowing for easy data management.

2. **Tree Map Visualization for Top 20 Countries**:
   - Created tree maps to visualize the top 20 countries based on total COVID-19 cases, deaths, recovered cases, and active cases.

3. **Trend Analysis of Confirmed Cases, Deaths, Recovered, and Active Cases**:
   - Created a line plot showing the trends of confirmed cases, deaths, recovered cases, and active cases over time with distinct colored lines.

4. **Population to Tests Ratio**:
   - Calculated the population-to-tests ratio by dividing the population by the total tests for each country.
   - Created a bar plot representing this ratio for the top 20 countries.

5. **Stacked Bar Plot for COVID-19 Cases Over Time**:
   - Created a stacked bar plot to show the breakdown of COVID-19 cases (Serious/Critical, Total Deaths, Total Recovered, Active Cases, and Total Cases) over time for the top 20 countries.

6. **Bar Chart for Top 20 Countries Based on Total Confirmed Cases**:
   - Analyzed and visualized the top 20 countries with the highest total confirmed COVID-19 cases using a horizontal bar chart.

7. **Bar Chart for Top 20 Countries Based on Total Deaths**:
   - Sorted the countries by total deaths and visualized the top 20 countries with the highest death toll using a horizontal bar chart.

8. **Bar Chart for Top 20 Countries Based on Active Cases**:
   - Created a bar chart for the top 20 countries with the highest number of active COVID-19 cases.

9. **Bar Chart for Top 20 Countries Based on Total Recovered Cases**:
   - Visualized the top 20 countries based on the total number of recovered COVID-19 cases.

10. **Pie Charts for the Worst Affected Countries**:
    - Focused on the 15 countries most affected by COVID-19 and created donut-shaped pie charts for the total cases, deaths, recovered, and active cases in these countries, segmented by WHO region.

11. **Deaths to Confirmed Cases Ratio**:
    - Calculated the ratio of deaths to confirmed cases and visualized it with a bar plot for all countries.

12. **Deaths to Recovered Cases Ratio**:
    - Created a bar plot for the ratio of deaths to recovered cases for all countries.

13. **Tests to Confirmed Cases Ratio**:
    - Analyzed and visualized the ratio of tests performed to confirmed cases in each country with a bar plot.

14. **Serious to Deaths Ratio**:
    - Created a bar plot visualizing the ratio of serious/critical cases to total deaths for each country.

15. **Visualization of Specific Country Data**:
    - Defined the function `country_visualization()` to automate the process of visualizing COVID-19 statistics for any country.
    - Used this function to visualize data for countries like **Brazil**, **US**, and **India**.
    - Utilized Plotly's `make_subplots` to generate multiple charts (Confirmed, Deaths, Recovered, and Active cases) for a given country.

### Project Structure:

- **`data_cleaning.py`**: Contains functions for data cleaning, removing missing values, and preparing the data for analysis.
- **`visualization.py`**: Includes functions to generate all the various plots, including bar charts, pie charts, tree maps, and line plots.
- **`main.py`**: Contains the main logic for importing data, processing, and visualizing it.
- **`data/`**: Folder containing the raw CSV files used for the analysis.
- **`requirements.txt`**: Lists all the Python libraries and dependencies required to run the project, including `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, etc.

### How to Run:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/covid19-data-analysis.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:
   ```bash
   python main.py
   ```

4. The visualizations can be viewed interactively through Plotly or exported to static images.

### Conclusion:

This project demonstrates the use of **Python** and **Plotly** to analyze and visualize COVID-19 data from around the world. With a focus on automation and interactive visualizations, this project provides a comprehensive approach to understanding the impact of COVID-19 globally.

Feel free to extend the project with additional analyses or visualizations tailored to specific regions or time frames!
