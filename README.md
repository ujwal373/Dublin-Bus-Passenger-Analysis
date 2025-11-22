# Dublin-Bus-Passenger-Analysis

## Overview
This project explores how Dublin Bus passenger numbers have changed over the past decade using R and Quarto. The goal is to understand long-term trends, monthly patterns, and major disruptions (including the COVID-19 period), and then build a simple forecasting model to predict future demand.

## Features
- Analyze historical passenger data from the Central Statistics Office (CSO)
- Clean and structure the dataset into yearly totals and month-level observations
- Visualize key patterns using line charts and heatmaps
- Identify seasonality, shocks, and recovery phases
- Build a forecasting model (ARIMA/ETS) to project future ridership
- Summarize insights in a Quarto PDF report

## Folder Structure
```
|-- .Rproj User
|-- .gitignore
|-- DublinBus Passenger Analysis.Rproj
|-- DublinBus.csv
|-- dublinbusanalysis.pdf
|-- dublinbusanalysis.qmd
```

## Installation
1. Ensure you have R and RStudio installed on your machine.
2. Install the required R packages:
   ```R
   install.packages(c("tidyverse", "lubridate", "forecast"))
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/ujwal373/Dublin-Bus-Passenger-Analysis.git
   ```

## Usage
1. Download the repository.
2. Keep the data file (`DublinBus.csv`) in the same directory as the `.qmd` file.
3. Open `dublinbusanalysis.qmd` in RStudio and run the code step by step.
4. Generate outputs in Quarto. Once satisfied with the outputs, render the document.
5. After rendering, the PDF report (`dublinbusanalysis.pdf`) will be available in your repository.

## Author Info
**Ujwal Mojidra**  
[GitHub](https://github.com/ujwal373) | [LinkedIn](https://www.linkedin.com/in/ujwal-mojidra-28098723a/)
