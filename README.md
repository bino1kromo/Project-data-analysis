# Data Analytics Project Dashboard 📊

This project is part of a data analysis pipeline which includes data preprocessing, data analysis, and visualization. The dashboard provides insights based on data from the project, and it is built using **Streamlit** for interactive visualization.

## Project Overview

The project analyzes sales data to extract useful business insights, including:
- Sales trends over time
- Product category performance
- Customer purchasing behavior
- Order delivery efficiency
- Top sellers analysis

## Features

- **Interactive Sales Trend Visualization**: Track sales and revenue growth over time.
- **Category Sales Analysis**: View performance by product categories and identify top-performing categories.
- **Customer Behavior Dashboard**: Analyze recency, frequency, monetary (RFM) metrics to gain insights into customer segments.
- **Order Delivery Performance**: Evaluate order processing and delivery times.
- **Top Seller Rankings**: View top sellers based on total sales.

## Setup Environment - Anaconda
To set up the environment using **Anaconda**, run the following:

```bash
conda create --name data-analysis-dashboard python=3.9
conda activate data-analysis-dashboard
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
Alternatively, you can set up the environment using pipenv with the following steps:
```bash
mkdir data_analytics_project
cd data_analytics_project
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run the Streamlit App
To start the dashboard locally, run the following command:
```
streamlit run dashboard.py
```

## File Overview
- Notebook_Proyek_Analisis_Data.ipynb: Jupyter notebook containing the full analysis workflow.
- dashboard.py: Streamlit app that generates an interactive dashboard based on the analysis.
- requirements.txt: List of required Python packages for the project.

## Data Insights
The project provides key insights into sales performance, customer segmentation, and order processing efficiency. Each insight is based on comprehensive data analysis performed in the notebook and visualized in the dashboard.
## Contact
For any questions or further inquiries, please reach out to the project maintainer at supmawatimeysi@gmail.com.


Make sure you customize the file paths, project descriptions, or contact details as per your actual project settings.
