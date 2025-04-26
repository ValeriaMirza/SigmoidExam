# Project Overview

This project was developed for the internal examination organized by A.O. "Sigmoid".  
The goal was to create a machine learning model to predict the `price_eur` column, documenting each step of the process.

# Structure

## `final.ipynb`
- Main notebook containing all relevant steps: loading and analyzing the dataset, handling missing values, feature engineering, feature selection, model training, and evaluation.
- Some models that took too long to run were not included in the code but are mentioned and explained in the markdown cells.

## `visualization.ipynb`
- Notebook dedicated to visualizing the dataset to better understand its structure and guide feature engineering decisions.

## `failed_attempts/`
- Folder containing notebooks and code for models and approaches that were tested but not selected.
- These were separated to keep the main notebook clean, fully runnable, and free of non-executing cells or errors.

# Notes

- Several algorithms were tested before deciding on the final model.
- Models that took too long to execute were not included directly in the final notebook, but they are referenced in the markdown explanations.
- Failed experiments and alternative ideas are stored in the `failed_attempts/` folder.
- The final model achieved an **R² score of 0.83**.
- Every step was commented and explained using markdown cells, even steps that might seem less important.
