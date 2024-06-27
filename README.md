
# Domestic Violence Against Women: In-depth Analysis

This project analyzes a dataset on domestic violence against women in a specific rural area of a developing country. The goal is to understand the correlation between various socio-economic factors and domestic violence, providing insights for effective interventions and policies.

## Table of Contents
- [Domestic Violence Against Women: In-depth Analysis](#domestic-violence-against-women-in-depth-analysis)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Dataset Description](#dataset-description)
  - [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Predictive Modeling](#predictive-modeling)
  - [Summary](#summary)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)

## Introduction
Domestic violence against women is a significant issue in many developing countries. Understanding the factors contributing to this violence can help in creating effective interventions and policies. This project provides a comprehensive analysis of these factors using the provided dataset.

## Dataset Description
The dataset includes the following columns:
- `SL. No`: Serial number of the record.
- `Age`: Age of the respondent.
- `Education`: Educational attainment of the respondent (primary, secondary, tertiary).
- `Employment`: Employment status of the respondent (employed, unemployed).
- `Income`: Income level of the respondent (0 indicating no income).
- `Marital status`: Marital status of the respondent (married, unmarried).
- `Violence`: Indicates whether the respondent has experienced domestic violence (yes or no).

## Data Cleaning and Preprocessing
The dataset required cleaning to correct typos and standardize the data:
- Replaced incorrect values in `Marital status`.
- Stripped whitespace from column names.
- Converted categorical variables to numeric for analysis.

## Exploratory Data Analysis
The exploratory data analysis includes:
- Descriptive statistics
- Correlation analysis
- Visualizations to explore relationships between variables

## Predictive Modeling
A predictive model using a Random Forest classifier was built to predict the likelihood of domestic violence based on socio-economic factors.

## Summary
The analysis revealed significant socio-economic factors influencing the occurrence of domestic violence. The key findings can help in designing targeted interventions and policies to address and mitigate domestic violence in the studied area.

## Installation
To run the notebook locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/debjit-mandal/Domestic-Violence-Analysis.git
   cd Domestic-Violence-Analysis
   ```

2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
To run the analysis, open the Jupyter notebook:
```sh
jupyter notebook Domestic_Violence_Analysis.ipynb
```

Follow the steps in the notebook to perform the analysis.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additional analyses.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
