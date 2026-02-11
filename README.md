# Assignment 3: Building Time Series Forecasts

A data science project focused on analyzing and forecasting retail sales data from Corporación Favorita stores using time series decomposition techniques.

This repository contains a Jupyter notebook that guides you through temporal data analysis to:
- Identify trends, seasonality, and anomalies in retail sales data
- Build forecasting models using time series decomposition
- Predict future sales patterns for specific stores and product families

## Repository Structure

```
Assignment-3/
├── README.md                    # This file
├── starter_notebook.ipynb       # Main analysis notebook with step-by-step instructions
└── data/                        # Data directory (CSV files not included in repo. Download from Kaggle)
    ├── train.csv               # Historical sales training data
    ├── holidays_events.csv     # Holiday and events information
    └── store.csv                # Store metadata
```

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Required Python libraries (see Installation section)

### Installation

1. **Clone this repository:**
   ```bash
   git clone <repository-url>
   cd Assignment-3
   ```

2. **Download the dataset:**
   - Go to the [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data) dataset on Kaggle
   - Click on the "Data" tab
   - Scroll down and select **Download All**
   - Extract the zip file and move the following files to the `data/` directory:
     - `train.csv`
     - `store.csv`
     - `holidays_events.csv`

3. **Install required libraries:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
   ```

### Running the Notebook

1. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```
   or
   ```bash
   jupyter lab
   ```

2. **Open the notebook:**
   - Navigate to `starter_notebook.ipynb`
   - Click to open

3. **Execute cells sequentially:**
   - Run each cell in order from top to bottom
   - Follow the instructions and complete the TODO sections
   - Checkpoints throughout the notebook help verify your progress