# CCSU-USGS-water-data


## Overview
This repository contains the work I have completed as part of undergraduate research at CCSU in 2026 under the Department of Mathematical Sciences.

## Repository contents

- `Discharge Temp Requests v3.ipynb` - This is the script used to pull data from the USGS API, process and clean it for use before exporting to .csv files.
- `Full Workflow.ipynb` - This is the cleaned up and combined version of all other scripts into a singular workflow. Recommended to check out first before other files as they contain many more remnants of me trying stuff out, some of which may or may not be of any use whatsoever.
- `Temperature Comparisons.ipynb` - Temperature comparisons Thompsonville - Middle Haddam
- `Discharge Lag Modeling.ipynb`
- `Piecewise Lag Modeling.ipynb`
- `Median DOY Visualizations.ipynb`
- `requirements.txt` - This contains all packages necessary to run the above notebook files.

## Software Requirements
Python 3 and Jupyter Notebook.

## Required Python packages:

- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
  
## Getting Started
*These instructions are for Windows operating systems. These may differ slightly for other operating systems.

Install Python 3 and Jupyter Notebook on your system, if not already installed. Download the files in the repository. Then, open your project folder where you have placed these scripts. Right click the empty space in the window and click "Open in Terminal" or, alternatively, click the folder path, type "cmd" and press enter. A command line window will appear.

Use the following to create a virtual environment in your project folder:
```
py -m venv .venv
```
If this command doesn't work, try the following instead (one should work, if not then you may not have python installed on your global path):
```
python -m venv .venv
```
```
python3 -m venv .venv
```

This will create a .venv folder within your project folder. This is where modules you install for this project will live (separate from the ones you already have on your system.) Run the following to activate it.
```
.venv\Scripts\activate.bat
```

Now, you can run this:
```
pip install requirements.txt
```
This command will install everything required to run the files within this repository within your virtual environment folder.

"Full Workflow.ipynb" does not require any other files outside of this repository. However, "Median DOY Visualizations.ipynb" does--consult Dr. Savatorova for the files required.
### Note: "Discharge Temp Requests v3.ipynb" and "Full Workflow.ipynb" require API keys from the USGS; you can acquire one at https://api.waterdata.usgs.gov/signup/
### This is necessary to pull all the data without getting timed out!
