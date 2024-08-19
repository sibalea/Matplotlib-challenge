## Matplotlib Challenge

## Overview

Welcome to the Matplotlib Challenge repository! This project demonstrates data visualization using Matplotlib, a powerful Python library for creating static, animated, and interactive visualizations. The goal of this challenge is to explore and analyze datasets through visualizations, providing insights and detailed analysis of the results.

## Project Description

In this repository, you will find various scripts and notebooks showcasing different types of visualizations created with Matplotlib. The project focuses on:

- Analyzing data trends and patterns
- Comparing datasets through graphical representation
- Highlighting key insights through visual means

## Datasets

This repository includes several datasets that are used for visualization and analysis. The datasets are provided in CSV format and can be found in the `data/` directory. Here is a brief description of each dataset:

1. **[Mouse_metadata.csv](data/Mouse_metadata.csv)**: The set contains the mice IDs, their gender, and the drug treatment each mouse received. It is a dataset provided by UCI for the Data Analytics Boot Camp Program students.

2. **[Study_results.csv](data/Study_results.csv)**: 
The set contains the mouse ID, the timepoint, the tumor Volume (mm3), the Metastatic Sites. It is a dataset provided by UCI for the Data analytics Boot Camp Program student.

## Analysis Process

The analysis process involves the following steps:

1. **Data Loading**: The datasets are loaded using Pandas to facilitate easy manipulation and cleaning.
2. **Data Cleaning**: Any necessary preprocessing steps, such as handling missing values, correcting data types, and normalizing data, are performed.
3. **Visualization Creation**: Various types of visualizations are created using Matplotlib, including line plots, bar charts, scatter plots, and histograms.
4. **Analysis and Interpretation**: The visualizations are analyzed to draw insights and identify trends or patterns. Key findings are summarized and interpreted based on the visualizations.

## Key Findings

Here are some key findings from the analysis:

- **Summary**
The study included 248 mice for a 45 days period, with 50.4% of them being male. The mice received numerous drugs to detect the most promising.

A Timepoint of 30 or lower indicates that not all mice completed the full treatment. Some possibly died along the way.

- **Analysis**: 
Capomulin and Ramicare treatments yield the most promising result, as they presented the lowest final tumor sizes in clean_data_merge.

The analysis of the result of a specific mouse treated with Capomulin  highlight the drug's effectiveness overtime.

In the boxplot by Drug Regimen, One of the promising drugs "Infubinol" has an outlier of 36.21.

There is a positive correlation of .84 between the weight of mice and their tumor size increase. Mice with higher weight tend to have a higher tumor volume.

## Getting Started

To replicate the analysis or create your own visualizations, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sibalea/Matplotlib-challenge.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd Matplotlib-challenge
   ```
3. **Run the Notebooks**:
   Open the Jupyter notebook (`pymaceuticals_analysis.ipynb`) to view the analysis and visualizations.

## Contributing

If you would like to contribute to this project, feel free to submit a pull request with your improvements or suggestions. Please make sure to follow the coding guidelines and include appropriate tests for your changes.

## Contact

For any questions or further information, please contact leaapovo@gmail.com.

## Acknowledgment
Adding Module5 assignment done with the expertise of [@rosericazondekon](https://github.com/rosericazondekon).