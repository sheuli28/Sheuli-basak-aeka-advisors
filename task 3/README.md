Cricket World Cup Analytics Dashboard

Task 3 – Business Intelligence Project

📌 Project Overview

This project focuses on building an interactive Business Intelligence (BI) dashboard to analyze historical Cricket World Cup data.
The goal is to convert raw cricket datasets into structured insights using data preprocessing, aggregation, and visualization techniques.

The dashboard is developed using Google Looker Studio and supports team-level and player-level analytics, comparative analysis, and trend exploration.

📊 Data Sources

The datasets used in this project were obtained from Kaggle, originally compiled from publicly available sources such as:

ESPN Cricinfo

Wikipedia

Data Coverage

Player batting performance statistics

Match-level data including teams and results

🗂 Dataset Availability

The complete datasets are not included in this repository due to:

Large file size

Direct usage within Google Looker Studio via Google Sheets

To provide clarity on data structure, sample CSV files are available in the data/ directory, demonstrating:

Schema design

Column formats

Data types

🛠 Data Preparation & Modeling

Data preprocessing was performed using Google Sheets, including:

Removal of missing and inconsistent records

Standardization of team and player names

Creation of calculated fields for analytical metrics

Logical relationships and aggregations were configured inside Looker Studio to enable multi-dimensional analysis.

⚙️ Tools & Technologies

Google Sheets

Data cleaning and preprocessing

Google Looker Studio

Data modeling

Calculated metrics

Interactive dashboards and filters

📈 Dashboard Features

The dashboard consists of the following analytical components:

🔹 Country-Level Analysis

Aggregated performance metrics by team

Dynamic filters for country selection

🔹 Player Performance Analysis

Total runs and highest individual scores

Ranking of top-performing players

🔹 Comparative Analytics

Player vs Player comparison

Side-by-side performance evaluation

🔹 High-Score Insights

Visualization of highest individual innings

Trend analysis across tournaments

🔹 Geospatial Visualization

Country-level performance mapping

Regional comparison based on team data

🌍 Geospatial Limitation

Venue or city-level geographic data was not available in the dataset.
As a result, geospatial analysis is implemented at the country level using team information.
