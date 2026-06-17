# Project Documentation

The project is structured using the CRISP-DM framework. Details about the framework can be found [here](https://www.datascience-pm.com/crisp-dm-2/).

## Project Details

> ⚠️ **Deliverable - 01.10.2026:** Add the names of all team members and their non-binding tasks. Invite all coaches to your repositories.

### Team Members

| Name | Major task |
|--------|------------|
| Student 1 |            |
| Student 2 |            |
| Student 3 |            |


### Project Name
> ⚠️ **Deliverable - 08.10.2026:** Define a project name and write a short pitch.

*Write a four-sentence pitch using [this](https://www.linkedin.com/posts/maabrahams_how-to-make-a-compelling-quick-pitch-activity-7179128237782970369-Qa6o/) guideline.*

---


# 1. Business Understanding
> ⚠️ **Deliverable - 15.10.2026:** Write a short problem statement and formulate goals.

## Problem Statement

*Describe the problem that should be solved in two sentences.*

## Goals

*Which goals are you aiming for? Goals should follow the [SMART](https://www.atlassian.com/blog/productivity/how-to-write-smart-goals) definition, with a focus on measurability.*

---

# 2. Data Understanding
> ⚠️ **Deliverable - 29.10.2026:** Define data sources and conduct an exploratory data analysis.

## Data Sources
*Consider [Kaggle](https://www.kaggle.com/datasets) or 
Swiss open data platforms (e.g. Open Government Data 
[Zurich](https://www.stadt-zuerich.ch/de/politik-und-verwaltung/statistik-und-daten/open-government-data.html), 
[Luzern](https://www.stadtluzern.ch/opengovernmentdata), or 
[Switzerland](https://opendata.swiss/de)) as potential data sources.*

| Data source | Description |
|-------------|-------------|
|             |             |
|             |             |


## Exploratory Data Analysis

*A hands-on definition of EDA can be found [here](https://www.geeksforgeeks.org/data-analysis/what-is-exploratory-data-analysis/). The EDA should be contained in a dedicated notebook.*

- Notebook to run the EDA: [01_data_understanding.ipynb](notebooks/01_data_understanding.ipynb)

### Data Quality

*Short description of the results from the EDA with respect to data quality issues, such as coverage, data types, missing values, etc.*

### Insights

*List insights from the EDA with respect to the problem statement. Is the data suitable for reaching your goals?*

### Visualizations

All visualizations can be found in `figures/eda`.

---

# 3. Data Preparation
*Data preparation (also known as feature engineering) consists of steps such as cleaning, filtering, joining, [aggregating](https://www.geeksforgeeks.org/python/grouping-and-aggregating-with-pandas/), [normalizing](https://www.geeksforgeeks.org/python/data-normalization-with-pandas/), and transforming. 
The goal is to have one dataset that contains all features and is ready to be used in the follow-up data modeling. 
All data preparation is contained in one notebook that may use modular code.*

- Notebook to run the data preparation: [02_data_preparation.ipynb](notebooks/02_data_preparation.ipynb)
- Reusable, modular code is outsourced to separate `.py` files: [src/data_preparation.py](src/data_preparation.py)

## Features

*List and describe each feature.*

| Feature | Description |
|---------|-------------|
|         |             |
|         |             |
|         |             |

---

# 4. Data Modeling
> ⚠️ **Deliverable - 26.11.2026:** Summarize the data modeling approach.

## Concept
*Describe the data modeling approach in a few sentences. 
Which major tasks have to be performed? 
Which types of models are used (why)? What are the results?*

## Implementation
*Make a reference to the notebook and scripts used for performing the data modeling.
Sketch a diagram that contains all major tasks and notes for the corresponding implementation.*

- Notebook to run the data modeling: [03_modeling.ipynb](notebooks/03_modeling.ipynb)
- Reusable, modular code is outsourced to separate `.py` files: [src/data_modeling.py](src/data_modeling.py)


# 5. Evaluation
> ⚠️ **Deliverable - 03.12.2026:** Perform the evaluation.

- Notebook to run the evaluation: [04_evaluation.ipynb](notebooks/04_evaluation.ipynb)

- All visualizations can be found in `figures/eval`.


## Results
*List major results. Results often come in the form of evaluation metrics. 
A short introduction can be found [here](https://www.ibm.com/think/topics/model-evaluation).*

## Interpretation
*Interpret results in the light of the problem statement. Could you solve the problem?
An important issue in the interpretation is practical applicability. Is your solution generalizable?*

## Limitations
*Describe weaknesses of your approach or the underlying data.*

---

# 6. Sustainable Development Goals
> ⚠️ **Deliverable - 10.12.2026:** Describe your results in the light of sustainability.

*The United Nations distinguishes 17 Sustainable Development Goals ([link](https://sdgs.un.org/goals)).
Put the results of your project in relation to at least one of these goals. A four-sentence description is sufficient.*
