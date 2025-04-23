# CSV Wizard 🧙‍♂️

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

A lightning-fast Python CLI to clean, analyze, and visualize CSV files with one command. 
Perfect for data analysts, researchers, and anyone tired of manual Excel work.

## 🚀 Features
- **Clean messy CSVs** (fix dates, remove dupes, handle missing values)
- **Auto-generate insights** (stats, outlier detection)
- **Visualize data** (histograms, scatter plots)
- **Slack/Email alerts** (optional)

## 📦 Install
bash
pip install csv-wizard

# Clean a file and save result
csv-wizard clean input.csv --output clean.csv

# Analyze with auto-visualization
csv-wizard analyze sales.csv --plot

# Interactive mode (guided cleaning)
csv-wizard interactive

🛠️ Built With
Pandas - Data manipulation

Click - Beautiful CLI interfaces

Matplotlib - Visualizations
