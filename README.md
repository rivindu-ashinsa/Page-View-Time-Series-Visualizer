# Page-View-Time-Series-Visualizer
Page View Time Series Visualizer - FreeCodeCamp Project (Data Analyzing with python) 
# Page View Time Series Visualizer

This project is part of the freeCodeCamp Data Analysis with Python certification. The objective of the project is to visualize page view data using Python and data visualization libraries.

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Visualizations](#visualizations)
  - [Line Plot](#line-plot)
  - [Bar Plot](#bar-plot)
  - [Box Plot](#box-plot)
- [License](#license)

## Overview
The project involves analyzing and visualizing time series data from freeCodeCamp's forum page views. The dataset includes daily page views from May 2016 to December 2019. The primary goal is to clean the data and create visualizations that help in understanding trends and patterns.

## Data
The dataset used in this project is provided by freeCodeCamp and includes the following columns:
- `date`: The date of the page view.
- `value`: The number of page views on that date.

The dataset is cleaned by removing the top and bottom 2.5% of page views to remove outliers.

## Installation
To run this project locally, you'll need to have Python installed along with the following libraries:
- pandas
- matplotlib
- seaborn

You can install these libraries using pip:
```bash
pip install pandas matplotlib seaborn
