# Ethanol and Electrification
This project analyzes the impact of electrification on the fuel efficiency of cars across various sizes. It also evaluates whether ethanol, despite being less polluting than gasoline, is more efficient. 

It focuses on Miles Per Gallon (MPG) for traditional vehicles and Miles Per Gallon equivalent (MPGe) for plug-in hybrids and electric vehicles. Data is sourced from fueleconomy.gov, and the methodology includes data scraping, cleaning, and visualization.

# Modules/Dependencies used
- **Data Scraping**: `requests` and `BeautifulSoup`
- **Data Analysis**: `pandas`(specifically DataFrames and `BytesIO`)
- **Data Visualisation**: `pyplot`

**Run this on your computer's command line for installation/updates)**
  ```bash
  pip install requests beautifulsoup4 pandas matplotlib
  ```

# Files
- **StepByStep_Fuel_Efficiency_Comparison.ipynb**: An interactive jupyter notebook to execute the data scraping, analysis and visualisation processes step-by-step
- **visualisation_diagrams**: A folder containing the respective visualisation bar plots for fuel efficiency comparisons of the various fuel types for quick reference
