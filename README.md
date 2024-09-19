## Overview
This project is designed to analyze and identify the gaps between demand and supply in the automotive supply chain using Power BI. The analysis aims to help organizations identify inefficiencies, enabling better decision-making for optimizing supply chain performance, reducing operational costs, and enhancing customer satisfaction.

## Problem Statement
Car manufacturers often face a mismatch between production (supply) and customer demand. This gap typically results in operational inefficiencies, customer dissatisfaction, and lost revenue opportunities. The project leverages an interactive Power BI dashboard to visualize and analyze the imbalance between the supply and demand of car sales, ultimately providing actionable insights to bridge these gaps.

## Objective
- To perform a visual analysis of the supply-demand gap within the automotive industry.
- To evaluate suppliers' performance in meeting demand and identify bottlenecks within the supply chain.
- To make actionable recommendations for improving supply chain efficiency and customer satisfaction.

## Data Source
- The dataset for this project was sourced from [Kaggle](https://www.kaggle.com), a public repository of datasets related to car sales and the automotive supply chain.

## Key Metrics
- **Total Sales**: The number of cars sold.
- **Total Supply**: The number of cars supplied by suppliers.
- **Demand-Supply Gap**: The difference between sales (demand) and supply.

## Methodology

### Data Preparation
- Cleaned and transformed the dataset using **Power Query** in Power BI to ensure accuracy.
- Data shaping involved handling missing values, normalizing metrics, and transforming fields for meaningful analysis.

### Data Analysis
- Calculated key metrics such as **Total Sales**, **Total Supply**, and the **Demand-Supply Gap** using **DAX formulas**.
- Insights were presented through interactive visuals, including bar charts, area charts, maps, and KPIs.
- Analyzed supplier performance to assess their ability to meet demand and identify any bottlenecks in the supply chain.

### Visualizations
- **Supply vs. Demand**: Comparison of the number of cars sold vs. cars shipped across models and regions.
- **Supplier Analysis**: Examined the number of shipments and the ability of suppliers to meet demand.
- **Customer Feedback Analysis**: Evaluated the correlation between supply chain issues and negative customer feedback.

## Insights
- Significant **supply-demand gaps** were identified, particularly for models like **Camino** and **Grand Fury**.
- Supply chain issues, such as **production slowdowns** or **logistical hold-ups**, caused supply shortages in mid-2019.
- Certain regions faced **severe supply delays**, leading to disgruntled customers and negative feedback.
- The total **demand-supply gap** amounted to **512 units**, with some models experiencing the largest shortfalls.

## Recommendations
- **Strengthen Supplier Relationships**: Work closely with suppliers, especially for high-demand models like **Camino** and **Grand Fury**, to ensure more consistent supply.
- **Address Regional Bottlenecks**: Allocate resources to resolve supply chain bottlenecks that are causing delays in specific regions.
- **Improve Customer Communication**: Enhance communication with customers regarding potential delays to manage expectations and reduce negative reviews.

## Conclusion
This Power BI dashboard provides a comprehensive analysis of the automotive supply chain, highlighting areas where demand does not meet supply. Organizations can bridge this gap by improving coordination with suppliers, addressing logistical challenges, and enhancing communication with customers.

## Tools Used
- **Power BI** for data visualization and analysis.
- **Power Query** for data cleaning and transformation.
- **DAX** for calculating key metrics and measures.

## How to Use
1. Clone this repository to your local machine.
2. Open the provided Power BI (.pbix) file.
3. Explore the dashboard to gain insights into the automotive supply chain.
4. Feel free to modify or add additional data for deeper analysis.

