#### Supermarket Swings: The Up-And-Down World of Grocery Costs

# Contents of this Repository
This repository contains the code, data, and documentation for analyzing grocery price trends over time. It includes: 
- Data retrieval scripts for fetching price data from the BLS API
- Time series analysis scripts for visualizing price fluctuations
- Statistical models for forecasting future grocery prices
- Documentation on the methods, software, and steps for reproduction

## Software and Platform
 Software Used: Python
 
 Required Packages: 
- pandas (for data manipulation)
- numpy (numerical calculation)
- matplotlib & seaborn (for visualization)
- statsmodels (for time series analysis)
- requests (for API data retrieval)
  
Platform: Compatible with Windows, Mac, and Linux

## Repository Structure
 /DATA               # Contains raw and processed data
 /SCRIPTS            # Jupyter notebook scripts for fetching and processing data
 /OUTPUT            # Outputs and figures from analysis
 LICENSE.md          # License information
 README.md           # Project documentation

## Reproducing the Results
To reproduce the results of this project, follow these steps:

##1. Clone the Repository
```bash
git clone https://github.com/kaitlinblakeslee/ctrlaltelite.git
cd ctrlaltelite
```

## 2. Install Dependencies
```bash
pip install pandas matplotlib seaborn statsmodels requests numpy
```

## 3. Download and Prepare Data
The data is retrieved from the BLS API using the data_fetch.py script.
Run the script to download and store grocery price data in the DATA/ folder.
Run M2_Project_2_Data_Retrieval.ipynb

## 4. Run Analysis Jupyter Notebooks
EDA_data_MD_Project2.ipynb: Visualizes trends and patterns in price fluctuations
SARIMA_M3_Analysis.ipynb: Uses a SARIMA model to predict future grocery price changes and assess volatility.

## 5. View Results
The results will be stored in the OUTPUT/ folder.
Key figures, CSVs, and analysis summaries can be found there for further exploration.
