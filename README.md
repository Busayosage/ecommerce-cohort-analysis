# E-commerce Cohort Analysis – Customer Retention Assessment

## Short Overview
This project applies cohort analysis to evaluate customer retention and purchasing behaviour in an e‑commerce platform. By grouping customers based on their first purchase date and tracking activity over time, the analysis identifies patterns in repeat purchases and churn.

## Business Problem
Online retailers must understand how long customers remain active after their initial purchase and what factors influence repeat buying. Without insight into retention, marketing spend and customer acquisition strategies may be misaligned, leading to lost revenue and high churn.

## Solution / Project Purpose
The project performs cohort analysis on transactional data to quantify retention trends, measure customer lifetime value and compare performance across acquisition cohorts. The aim is to help decision‑makers identify which cohorts perform well and where engagement drops off.

## Key Features
- Segments customers into cohorts based on their sign‑up or first purchase date.
- Calculates retention rates and customer lifetime over weekly and monthly periods.
- Visualises cohort retention in heatmaps for intuitive interpretation.
- Compares performance across different cohorts to identify best‑performing segments.

## Tools and Technologies
- Python: Pandas and NumPy for data manipulation.
- Matplotlib and Seaborn for cohort heatmap visualisations.
- Jupyter Notebook environment.
- Git and GitHub for version control.

## Workflow / Method
1. Clean and preprocess transactional and inventory datasets.
2. Create cohorts by customer sign‑up or first purchase date.
3. Calculate retention rates and compute cohort metrics.
4. Visualise retention in cohort heatmaps to identify trends.
5. Interpret results to inform marketing and customer engagement strategies.

## Key Insights or Outcomes
Cohort analysis reveals how customer engagement decays over time and highlights cohorts with stronger loyalty. The results help prioritise marketing efforts and tailor retention strategies to specific customer segments.

## Business or Practical Impact
Understanding retention patterns enables e‑commerce businesses to optimise marketing spend, improve customer lifetime value and reduce churn. Data‑driven decisions can target interventions to cohorts with the highest growth potential.

## Project Structure
- Dataset_ecommerce.csv – customer purchase transactions  
- Historical_Product_Demand.csv – product demand trends  
- inventory_dataset.csv – inventory and stock data  
- README.md – project overview and analysis

## How to Run or View
Clone the repository and open the Jupyter notebook to explore the analysis. Use Python libraries to load the datasets, run the cohort calculations and generate visualisations. Adjust the cohort intervals or filters to explore different retention scenarios.

## Future Improvements
- Incorporate additional customer attributes such as marketing channel or region to enrich cohort segmentation.
- Build interactive dashboards to allow stakeholders to explore cohort metrics without code.
- Integrate the analysis with business intelligence tools for automated reporting.
