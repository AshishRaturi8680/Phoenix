# AI003 – Workstream 3 (Logging, Testing & Documentation)

This module implements logging, testing, and comparison functionality for the AI003 Data Cleaning Pipeline.

## Overview
The purpose of this module is to track data transformations, validate cleaning effectiveness, and provide clear before-vs-after insights. It supports early-stage development using dummy data and is designed to integrate with the full pipeline later.

## Files
- `run_demo.py` – main script to execute the pipeline
- `logging_utils.py` – functions to log missing values, duplicates, and transformations
- `comparison.py` – compares dataset quality before and after cleaning
- `test_data.csv` – sample dataset with intentional data issues
- `cleaned_output.csv` – generated output after cleaning
- `documentation.md` – detailed AI003 documentation

## Features
- Logs missing values detected
- Logs duplicate rows removed
- Logs applied transformations
- Provides before vs after dataset comparison
- Generates cleaned dataset output

## How to Run
```bash
cd ai-ml/cleaning/logging
py run_demo.py