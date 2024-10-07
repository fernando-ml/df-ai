# Anonymized Research Repository

## Overview

This repository contains code and data for our research paper on [brief description of research topic]. The project focuses on image generation and analysis, utilizing multiple raters' assessments.

## Repository Structure
├── generation.py
├── requirements.txt
├── table_combination.ipynb
├── images/
│ ├── sample_images/
│ └── generated_plots/
└── data/
├── Rater1_image_ratings.xlsx
├── Rater2_image_ratings.xlsx
├── Rater3_image_ratings.xlsx
├── Rater4_image_ratings.xlsx
└── consolidated_final.xlsx


## Files Description

### generation.py
This script is responsible for generating images used in the study.

### requirements.txt
Contains a list of Python libraries required to run the code in this repository.

### table_combination.ipynb
A Jupyter notebook that:
1. Creates a consolidated dataset from individual rater files
2. Performs statistical analysis on the data
3. Generates plots and visualizations presented in the paper

## Directories

### images/
Contains sample images used in the study and plots generated by `table_combination.ipynb`.

### data/
Stores the raw data files:
- Individual Excel files for each rater's image ratings
- A consolidated final dataset combining all raters' assessments

[Dataset Link]([URL](https://zenodo.org/records/13871978?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6ImM5NzcxNzJiLWIxNWEtNDhjNC1hOTY4LTE3ZjhlMmIwNTMwOCIsImRhdGEiOnt9LCJyYW5kb20iOiI4OTE5ZTA5OWRjYmQxZDVhMjAxOTY1ZjFkMTAwMGI5MiJ9.7QyPXvP8W28lH-1FqpKmVfIUEGPE-bQOfPmtDpM30PyRXjTtL4PPZQcGaMpnsf_YhmR9wfQ46ORu5YDb--L7kw))
