![DOH_logo](https://user-images.githubusercontent.com/108571876/235377509-dc2970cd-dc6f-493c-abde-c47cd11ac33d.png)


# Florida HIV, AIDS, and Death Rates Analysis (2012-2021)

This repository contains an analysis of HIV, AIDS, and death rates in Florida by county, for the years 2012-2021. The analysis is done using Python, pandas, and Plotly for visualization.

## Overview

The project aims to visualize the trends in HIV, AIDS, and death rates in Florida by county between 2012 and 2021. The data is first preprocessed to extract the relevant information, and then visualized using an interactive bar chart.

## Data

The data used in this project is a CSV file containing information about HIV, AIDS, and death rates for each county in Florida, as well as the year the data was recorded. The data was obtained from the Florida Department of Health (https://www.flhealthcharts.gov/ChartsDashboards/rdPage.aspx?rdReport=HIVAIDS.TenYrsRpt&cid=0471) in which the CSV files for HIV and AIDs where both downloaded. The death related to HIV/AIDs was also obtained from the Florida Department of Health (https://www.flhealthcharts.gov/ChartsDashboards/rdPage.aspx?rdReport=Death.TenYrsRpt&cid=122). For dealth related to HIV/AIDs age-adjusted data was used to make sure that the differences seen because of differences in the age distributions between different populations or for the same populations over time. It should be noted that the HIV and AIDs data did not have the option to adjust for age. Each CSV file was reshaped in Excel before being merged in Python.

## Dependencies

- Python 3
- pandas
- Plotly
- DataPane

## Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/florida-hiv-aids-death-rates.git
cd florida-hiv-aids-death-rates
```

2. Install the required libraries:

```bash
pip install pandas plotly datapane
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook
```

## Usage

Open the Jupyter Notebook file (`Analyzing County Level HIV & AIDs Data in Python.ipynb`) and run the cells to perform the analysis and generate the interactive bar chart. The chart includes a slider to filter the data by year.

The visualization will be available here: https://cloud.datapane.com/reports/P3XOOMA/hiv-aids/
