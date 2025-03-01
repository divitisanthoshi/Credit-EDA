# Credit EDA - Exploratory Data Analysis

## Overview
This project performs Exploratory Data Analysis (EDA) on credit-related datasets to identify patterns, handle missing values, detect outliers, and derive insights from customer application and previous application data. The analysis helps in understanding customer credit behavior and identifying potential risks.

## Features
- Reads and processes application and previous application datasets.
- Cleans and handles missing values, removing unnecessary columns.
- Standardizes and bins categorical and numerical values.
- Performs univariate, bivariate, and multivariate analyses.
- Identifies correlations and key insights from the data.
- Merges datasets for deeper analysis.
- Generates visualizations to highlight findings.

## Requirements
Ensure you have the following dependencies installed before running the script:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy

Install dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scipy
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```
2. Navigate to the project directory:
   ```bash
   cd yourrepository
   ```
3. Ensure the required datasets (`application_data.csv` and `previous_application.csv`) are present in the working directory.
4. Run the script using:
   ```bash
   python credit_eda.py
   ```
5. The script will process the data, generate insights, and produce visualizations.

## Key Insights
- Most unsuccessful payments are associated with loans for 'Repairs'.
- Customers in the 'With Parents' housing type have fewer payment defaults.
- The 'Working' income type has a higher rate of unsuccessful payments.
- Customers in 'Co-op apartments' have higher payment difficulties.

## Output
- Processed data with handled missing values and standardized columns.
- Visualizations for data distribution, outliers, and correlations.
- Analytical insights to support credit risk assessment.

## Contributing
Contributions are welcome! If you want to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request.

