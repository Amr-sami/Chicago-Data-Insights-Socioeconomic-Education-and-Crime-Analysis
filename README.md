# Chicago Insights

## Overview

**Chicago Insights** is a data analysis project that explores the socio-economic conditions, public school performance, and crime statistics in Chicago. This project leverages three distinct datasets to uncover insights and trends within the city.

## Datasets

This project utilizes the following datasets:

1. **Socioeconomic Indicators in Chicago**:
   - Contains key socioeconomic indicators and a hardship index for each Chicago community area.
   - Data source: [Chicago Data Portal - Socioeconomic Indicators](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2)

2. **Chicago Public Schools**:
   - Includes performance data for public schools in Chicago for the 2011-2012 school year.
   - Data source: [Chicago Data Portal - Public Schools](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t)

3. **Chicago Crime Data**:
   - Contains reported incidents of crime in Chicago from 2001 to the present.
   - Data source: [Chicago Data Portal - Crime Data](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)

## Project Structure

- **`ChicagoInsights.ipynb`**: The main Jupyter notebook containing data loading, cleaning, and analysis.
- **`data/`**: A directory containing the raw datasets (if included).
- **`README.md`**: This file, providing an overview of the project.
- **`FinalDB.db`**: The SQLite database created to store and query the datasets.

## Objectives

1. Load and store the datasets into an SQLite database.
2. Analyze and explore the data using SQL queries.
3. Uncover insights related to Chicago's socioeconomic conditions, public school performance, and crime patterns.

## Setup and Usage

### Requirements

- Python 3.x
- Pandas
- SQLite
- ipython-sql

### Setup

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/chicago-insights.git
    cd chicago-insights
    ```

2. **Install the required packages**:
    ```sh
    pip install pandas ipython-sql sqlite3
    ```

3. **Run the Jupyter Notebook**:
    ```sh
    jupyter notebook ChicagoInsights.ipynb
    ```

4. **Explore the Data**:
    - The notebook contains all the code needed to load data into the SQLite database, perform queries, and visualize insights.

## Key Insights

- **Correlation Between Income and Hardship**: There is a strong negative correlation between per capita income and hardship index in Chicago's community areas.
- **Crime Patterns**: Analysis of crime data reveals the most frequent types of crime and the areas most affected by them.
- **Public School Performance**: The project also explores how school performance correlates with community socioeconomics.

## Conclusion

**Chicago Insights** provides a comprehensive look at the interplay between socioeconomic factors, education, and crime in one of America's largest cities. The project demonstrates how data can be used to uncover important trends and inform policy decisions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please contact [samyamr819@gmail.com].
