# Clinical Trial Data Analysis

This repository contains code and data analysis for clinical trial datasets. The analysis focuses on cleaning, processing, and extracting insights from clinical trial records, condition hierarchies, and pharmaceutical company data.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Technologies Used](#technologies-used)
4. [Key Features](#key-features)
5. [Installation and Setup](#installation-and-setup)
6. [Usage](#usage)
7. [Results](#results)
8. [Conclusion](#conclusion)

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
- **Libraries**:
  - Pandas
  - Matplotlib
  - Seaborn
  - Tabulate
- **Tools**: Jupyter Notebook

## Key Features
- **Distinct Studies**: The dataset includes a total of `X` unique clinical trials (where `X` is calculated dynamically).
- **Trial Types**: The most frequent trial types are extracted and displayed in descending order of occurrence.
- **Top 5 Conditions**: Frequently studied conditions are identified and visualized.
- **Hierarchy Roots**: Hierarchical classification of conditions reveals the top 5 most common roots.
- **Non-Pharmaceutical Sponsors**: The top 10 non-pharmaceutical sponsors are listed based on the number of trials.
- **Monthly Completion Trends**: A bar plot shows the number of completed studies each month in 2021.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/aritro98/Clinical-Trial-Data-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Clinical-Trial-Data-Analysis
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Clinical_Trial_Data_Analysis.ipynb
   ```
2. Analyze trial types, conditions, and sponsor contributions by running the provided code cells.
3. Visualize monthly completion trends and extend the analysis with custom queries.

## Results
1. **Distinct Studies**: A total of `X` unique clinical trials were identified.
2. **Trial Types**: The most common trial types, including interventional and observational, were highlighted.
3. **Top Conditions**: Conditions like diabetes, cancer, and hypertension were among the most frequently studied.
4. **Hierarchy Roots**: The top 5 most frequent hierarchy roots from the condition classification were extracted.
5. **Sponsor Insights**: A list of non-pharmaceutical sponsors contributing significantly to clinical trials was generated.
6. **Monthly Trends**: Visualization of monthly completion trends for 2021 revealed patterns in study completions.
