# Clinical Trial Data Analysis

This repository contains code and data analysis for clinical trial datasets. The analysis focuses on cleaning, processing, and extracting insights from clinical trial records, condition hierarchies, and pharmaceutical company data.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Technologies Used](#technologies-used)
4. [Key Features](#key-features)
5. [Installation and Setup](#installation-and-setup)
6. [Steps for Data Analysis](#steps-for-data-analysis)
7. [Usage](#usage)
8. [Results](#results)

## Project Overview

This project involves analyzing clinical trial datasets to extract valuable insights about:
- The types of clinical trials conducted.
- The most frequent conditions studied.
- Non-pharmaceutical sponsors.
- Monthly completion trends for the year 2021.

The repository demonstrates a comprehensive data analysis pipeline using Python.

## Dataset Description

The datasets used in this project include:

1. **clinicaltrial_2021.csv**:
   - Contains clinical trial information such as sponsors, types, conditions, start and completion dates, and statuses.
   
2. **mesh.csv**:
   - Maps conditions to hierarchical codes for classification.
   
3. **pharma.csv**:
   - Lists pharmaceutical companies and related information.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: pandas, matplotlib, seaborn
- **Tools**: Jupyter Notebook / Google Colab

## Steps for Data Analysis

1. **Load Data**:
   - Import clinical trial, mesh, and pharmaceutical datasets into pandas DataFrames.

2. **Data Cleaning**:
   - Remove duplicate entries.
   - Drop rows with missing values in critical columns such as `Id`, `Sponsor`, `Type`, `Conditions`, `Start`, and `Completion`.
   - Convert date columns (`Start`, `Completion`) to datetime format.

3. **Data Analysis**:
   - Count distinct clinical trials.
   - Determine the frequency of each trial type.
   - Identify the top 5 conditions studied.
   - Extract the most frequent hierarchy roots from the condition mapping.
   - List the top 10 non-pharmaceutical sponsors.
   - Analyze monthly completion trends for the year 2021.

4. **Visualization**:
   - Use bar plots to visualize the monthly completion trends.
   - Apply pastel palettes for accessibility.

## Key Features

### 1. Distinct Studies:
- The dataset includes a total of `X` unique clinical trials (where `X` is calculated dynamically).

### 2. Trial Types:
- The most frequent trial types are extracted and displayed in descending order of occurrence.

### 3. Top 5 Conditions:
- Frequently studied conditions are identified and visualized.

### 4. Hierarchy Roots:
- Hierarchical classification of conditions reveals the top 5 most common roots.

### 5. Non-Pharmaceutical Sponsors:
- The top 10 non-pharmaceutical sponsors are listed based on the number of trials.

### 6. Monthly Completion Trends:
- A bar plot shows the number of completed studies each month in 2021.

## Usage

1. Clone the repository and install dependencies (see [How to Run](#how-to-run)).
2. Open the Jupyter Notebook or run the Python script to explore the datasets.
3. Analyze trial types and identify the most frequent conditions studied.
4. Discover the top non-pharmaceutical sponsors based on trial contributions.
5. Generate visualizations, such as monthly trends in completed studies for 2021.
6. Extend the analysis by integrating additional datasets or custom queries.

## Results

1. **Distinct Studies**:
   - A total of `X` unique clinical trials were identified.

2. **Trial Types**:
   - The most common trial types, including interventional and observational, were highlighted.

3. **Top Conditions**:
   - Conditions like diabetes, cancer, and hypertension were among the most frequently studied.

4. **Sponsor Insights**:
   - A list of non-pharmaceutical sponsors contributing significantly to clinical trials was generated.

5. **Monthly Trends**:
   - Visualization of monthly completion trends for 2021 revealed patterns in study completions.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/clinical-trial-analysis.git
   ```

2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook clinical_trial_analysis.ipynb
   ```

4. Run the analysis script (optional):
   ```bash
   python clinical_trial_analysis.py
   ```

5. View the results and visualizations.
