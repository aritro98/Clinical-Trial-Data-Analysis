# Clinical Trial Data Analysis

This project demonstrates a structured approach to analyzing clinical trial datasets using Python. It focuses on deriving actionable insights by cleaning, processing, and visualizing data related to trial records, condition hierarchies, and sponsor contributions.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Technologies Used](#technologies-used)
4. [Key Features](#key-features)
5. [Installation and Setup](#installation-and-setup)
6. [Usage](#usage)
7. [Results](#results)

## Project Overview
This project provides an in-depth analysis of clinical trial datasets to uncover meaningful insights into trial trends, frequently studied conditions, and key sponsor contributions. By leveraging Python for data cleaning, exploration, and visualization, it highlights the distribution of trial types, identifies top conditions and sponsors, and visualizes monthly completion patterns for 2021.

The aim of this analysis is to shed light on clinical trial distribution, prevalent conditions, and legal aspects within the pharmaceutical industry.

## Dataset Description
The datasets used in this project include:
1. **Clinical Trial Dataset**:
   - This dataset contains information about clinical trials conducted in 2021. It includes details such as trial phases, participant demographics, treatment protocols, and outcomes.
   - Researchers can use this data to understand trends, evaluate treatment efficacy, and identify areas for further investigation.
2. **Medical Subject Headings Dataset**:
   - Mesh terms are standardized vocabulary descriptors used to categorize biomedical literature. They help organize and retrieve relevant articles.
   - In this analysis, Mesh data is used to link clinical trial data to specific medical conditions, treatments, or interventions. Researchers can explore which Mesh terms are most prevalent in the trials.
3. **Pharmaceutical Company Dataset**:
   - This dataset provides insights into pharmaceutical companies. It may include information about company size, revenue, research focus, and legal history.
   - Researchers can analyze legal actions involving pharmaceutical firms, such as patent disputes, regulatory violations, or product liability cases.

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
1. **Distinct Studies**: The analysis identified a significant number of unique clinical trials.
2. **Trial Types**: The most common trial types, including interventional and observational, were highlighted.
3. **Top Conditions**: Conditions like diabetes, cancer, and hypertension were among the most frequently studied.
4. **Hierarchy Roots**: The top 5 most frequent hierarchy roots from the condition classification were extracted.
5. **Sponsor Insights**: A list of non-pharmaceutical sponsors contributing significantly to clinical trials was generated.
6. **Monthly Trends**: Visualization of monthly completion trends for 2021 revealed patterns in study completions.
