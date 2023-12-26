# Labor Force Analysis Project

## Overview

This repository contains the code and analysis for exploring labor force dynamics in Canada based on the Statistics Canada dataset. The project investigates the relationships between age, gender, and labor force status, providing insights into employment patterns across various geographical levels.

## Table Information

- **Table Name:** Labour force status by age and gender: Canada, provinces and territories, census divisions and census subdivisions
- **Table Code:** 98-10-0485-01
- **Release Date:** November 15, 2023
- **Geography:** Canada, Province or territory, Census division, Census subdivision
- **Universe:** Population aged 15 years and over in private households, 2021 Census — 25% Sample data
- **Variables:** Age (15A), Labour force status (8), Gender (3)

## Code Structure

The project includes Python scripts (`LaborForceAnalysis.ipynb`) for data preprocessing, exploration, and clustering. Libraries such as pandas, NumPy, scikit-learn, seaborn, and matplotlib are used. The clustering approach involves KMeans for numerical features and KPrototypes for a combination of numerical and categorical features.

## Getting Started

1. Install the required libraries: `pip install pandas numpy scikit-learn seaborn matplotlib kmodes`
2. Run the Jupyter notebook `LaborForceAnalysis.ipynb` for step-by-step analysis.

## File Descriptions

- `LaborForceAnalysis.ipynb`: Jupyter notebook containing the project code.
- `Data/`: Directory containing the dataset and any intermediate data files.

## Citation

- **Statistics Canada Table:** [Labour force status by age and gender: Canada, provinces and territories, census divisions and census subdivisions](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=9810048501)
- **DOI:** [https://doi.org/10.25318/9810048501-eng](https://doi.org/10.25318/9810048501-eng)

Feel free to explore and adapt the code to gain insights into the labor force landscape in Canada.
