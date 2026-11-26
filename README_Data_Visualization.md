# Oil and Gas Production Analysis -- Data Visualization

## Project Overview

This project focuses on visualizing 2024 oil and gas production data
using Python.

It is part of my Data Analytics Internship with CodeAlpha. The project
uses data visualization techniques to present production trends, compare
well and operator performance, and examine relationships between
different production variables.

The visualizations provide a clearer understanding of production
patterns and demonstrate how data analysis can support petroleum
engineering activities.

## Project Objectives

The main objectives of this project are to:

-   Visualize monthly oil, gas, water and injection production trends.
-   Compare production performance across individual wells.
-   Examine relationships between oil, gas and water production.
-   Analyze Water-Oil Ratio (WOR) across wells.
-   Compare production contributions across operators.
-   Communicate important production insights through charts.

## Dataset Description

The project uses a 2024 Oil and Gas Production dataset containing
**62,836 records and 19 columns**.

The dataset includes information such as:

-   Production dates
-   API well numbers
-   Operator names
-   Monthly oil production volumes
-   Monthly gas production volumes
-   Monthly water production volumes
-   Injection volumes
-   Other production-related information

The dataset is included in the `data` folder of this repository.

## Tools and Libraries

The following tools and Python libraries were used:

-   **Python:** Programming language used for the analysis.
-   **Pandas:** Data loading, manipulation and aggregation.
-   **NumPy:** Numerical operations and calculations.
-   **Matplotlib:** Creation of charts and visualizations.
-   **Jupyter Notebook:** Development and execution environment.

## Visualizations and Analysis

The notebook covers the following areas:

### 1. Monthly Production Trends

-   Monthly oil production.
-   Monthly gas production.
-   Monthly water production.
-   Monthly injection volumes.
-   Indexed comparison of production trends using January as the base
    month (100).

### 2. Well Production Analysis

-   Top 10 oil-producing wells.
-   Top 10 gas-producing wells.
-   Top 10 water-producing wells.

### 3. Production Relationships

-   Oil-water production scatter plot.
-   Oil-gas production scatter plot.
-   Correlation analysis and comparison of production relationships.

### 4. Water-Oil Ratio Analysis

-   Calculation of Water-Oil Ratio (WOR) for individual wells.
-   WOR distribution histogram.
-   Top 10 wells with the highest WOR values.

### 5. Operator Production Analysis

-   Top 10 oil-producing operators.
-   Top 10 gas-producing operators.
-   Top 10 water-producing operators.
-   Comparison of oil, gas and water production among the top
    oil-producing operators.

## Key Findings

Some of the major findings from the analysis include:

-   December recorded the highest monthly oil production, while
    September recorded the lowest.
-   Shell Offshore Incorporated recorded the highest total oil and gas
    production among the operators.
-   BP Exploration and Production Incorporated recorded the highest
    total water production.
-   The oil-gas production correlation was approximately **0.6469**,
    indicating a moderate positive linear relationship.
-   The oil-water production correlation was approximately **0.2830**,
    indicating a weak positive linear relationship.

These findings describe patterns observed in the dataset and do not
establish causal relationships.

## Repository Structure

``` text
CodeAlpha_Data_Visualization/
│
├── CodeAlpha_Data_Visualization.ipynb
│
├── data/
│   └── ogora2024delimit.txt
│
├── README.md
│
└── requirements.txt
```

## How to Run the Project

1.  Clone or download this repository.
2.  Ensure Python is installed.
3.  Install the required libraries:

``` bash
pip install -r requirements.txt
```

4.  Open Jupyter Notebook:

``` bash
jupyter notebook
```

5.  Open `CodeAlpha_Data_Visualization.ipynb` and run the notebook
    cells.

**Note:** Keep the dataset inside the `data` folder so the notebook can
locate it using its relative file path.

## Conclusion

This project demonstrates the use of Python for visualizing and
communicating insights from oil and gas production data.

Through different visualization techniques, I explored production
trends, compared well and operator performance, examined relationships
between production variables, and analyzed Water-Oil Ratio.

The project has also strengthened my practical skills in Python, data
analysis and visualization, while improving my understanding of how
production data can provide useful insights in petroleum engineering.

------------------------------------------------------------------------

**Project:** Oil and Gas Production Analysis -- Data Visualization\
**Internship:** CodeAlpha Data Analytics Internship\
**Author:** Falaju Oluwatise
