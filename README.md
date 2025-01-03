# Ethanol and Electrification
This project analyses the impact of electrification on the fuel efficiency of cars across various vehicle classes. It also evaluates whether ethanol, despite being less polluting than gasoline, is more efficient. 

It focuses on comparing Miles Per Gallon(MPG)[^1] and Miles Per Gallon equivalent(MPGe)[^2] metrics. Data is sourced from fueleconomy.gov, and the methodology includes data scraping, cleaning, and analysis/visualisation.

[^1]: MPG(Miles Per Gallon) measures how many miles a vehicle can travel using one gallon of fuel, used in this project for gasoline, ethanol and regular hybrid vehicles.
[^2]: MPGe(Miles Per Gallon equivalent) msasures how many miles a vehicle can travel using the ernrgy equivalent of one gallon of fuel, used in this project for plug-in hybrids and electric vehicles.
# Modules/Dependencies used
- **Data Scraping**: `requests` and `BeautifulSoup`
- **Data Cleaning/Analysis**: `pandas` and `io`(specifically `DataFrame` and `BytesIO`)
- **Data Visualisation**: `matplotlib.pyplot`

**Run this on your computer's command line for installation/update of modules**
  ```bash
  pip install requests beautifulsoup4 pandas matplotlib
  ```

# Files
- **StepByStep_Fuel_Efficiency_Comparison.ipynb**: An interactive jupyter notebook that can be downloaded locally to execute the data scraping, analysis and visualisation processes step-by-step
- **visualisation_diagrams**: A folder containing the respective visualisation bar plots that can be downloaded showing fuel efficiency comparisons across the various fuel types and vehicle classes for quick reference
  ## Bonus
    - **Electrification_Correlation.ipynb**: The second part of the data analysis project, focusing on the trends of how fuel efficiency varies with the degree of electrification of cars in 2 different vehicle classes in different driving categories. It requires the **StepByStep_Fuel_Efficiency_Comparison.ipynb** as a dependency to run properly.
