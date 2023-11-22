# Global Economic Indicators Dashboard
## Overview
This project provides a visual exploration of global economic indicators, leveraging data extracted from The World Bank. It aims to present interactive insights into population, GDP, and temperature changes over time. The dashboard allows users to drill down into specific country data to reveal more detailed economic indicators.

## Data Extraction
The extraction process involves parsing JSON formatted data sources. The countries.json file provides the core country data, including population and GDP statistics.

## Data Preprocessing
The raw data underwent preprocessing to ensure accuracy and relevance. This involved cleaning, transforming, and structuring the data to fit the needs of the visualization. Key steps included normalization of figures, handling missing values, and converting data into a format suitable for analysis.


## Visualization and Insights
### The dashboard answers several important questions, such as:
- What is the population and GDP of various countries?
- How does population density correlate with economic output?
- What are the GDP growth trends over the past decades?
- How has the average temperature changed globally over the years?
### From the dashboard, we can glean insights such as:
- Countries with higher population densities do not necessarily have a high GDP per capita.
- Economic growth fluctuates significantly over time, with some countries showing resilience and others volatility.
- The global temperature graph illustrates an upward trend, aligning with concerns about global warming.

## Files Description
- `images/`: Folder containing Icons and Images used in the Dashboard.
- `countries.json`: JSON source file with country data.
- `countries-indicators.csv`: Excel CSV file with economic indicators.
- `nasa-global-temp-data.csv`: Excel CSV file with global temperature data.
- `world-countries-geomap.json`: JSON source file with geographical mapping data.

## How to Use
To interact with the dashboard:
1. Clone the repository to your local machine.
2. Open the provided dashboard file with a compatible data visualization tool.
3. Explore the data by interacting with different components, such as graphs and maps.
4. Use the 'Drillthrough' feature on visuals for detailed data about a country.


