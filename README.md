# Satellite Conjunction Analysis

This repository contains a Jupyter notebook for analyzing satellite conjunctions using data from [NORAD](https://celestrak.org/SOCRATES/socrates-format.php).

## Overview

The `Conjunction_Analysis.ipynb` notebook provides an interactive dashboard to visualize the daily number of conjunctions for satellites over a specified date range. It allows filtering by NORAD ID, relative speed, and range.

## Interactive Dashboard

The dashboard includes the following interactive features:

- **NORAD ID Dropdown**: Select the NORAD ID of the satellite of interest.
- **Date Range Slider**: Choose the date range to analyze the conjunction data.
- **Relative Speed Slider**: Filter the data by the relative speed of the satellites.
- **Range Slider**: Filter the data by the range at the time of closest approach.

## Usage

To use the notebook:

1. Ensure you have Jupyter Notebook or JupyterLab installed.
2. Install the required libraries: `pandas`, `matplotlib`, `seaborn`, and `ipywidgets`.
3. Run the notebook and use the interactive widgets to filter and visualize the data.

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- ipywidgets

## Data

The analysis is based on a dataset of satellite conjunctions. Which solves some given questions with Visualisations and High level analytics.
A) Derive high level analytics from the whole data set for a single day. In other
words, derive general analytics of the whole set of conjunction scenarios (for e.g.
number of conjunctions among active satellites). The analytics should be intuitive
and represented in an easily understandable format.

B) Represent the conjunctions data of a single satellite or a satellite constellation.
The analytics should be intuitive, represented in an easily understandable format and
should enable decision making from a satellite operator’s point of view.

Question 2
Use the whole dataset that spans about five days. Derive analytics and visualise the
data/analytics accounting for the evolution from the first day (for e.g. the number of
conjunctions of the RSO having NORAD ID 12345 over 7 days of analysis)
The data includes the NORAD catalog IDs, object names, times of closest approach (TCA), relative speeds, and ranges.

## Visualization Example

Below is an example visualization from the notebook, showing the daily number of conjunctions for a selected satellite:

![Daily Count of Active Satellite Conjunction Visualization](https://github.com/yoyo-gitroi/Conjunction_analysis/assets/67566026/b0561cd3-b123-45d3-98d5-09e222a037b1)

## Contributing

Contributions to the notebook are welcome. Please fork the repository and submit a pull request with your changes.
Created By [Yash Vats](ywaths@gmail.com)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
