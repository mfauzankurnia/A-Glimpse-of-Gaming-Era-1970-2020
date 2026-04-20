-- The Bigger Picture

Project Title: A Glimpse of Gaming Era 1970-2020

Dataset: Video Game Sales & Industry Data (1980 - 2024). Source: www.kaggle.com (real data)

Programming Language: Phyton

Software: Microsoft Excel, Google Colab, Google Sheet and Looker Data Studio

Method: Exploratory Data Analysis

Scope Analysis: This analysis focuses on evaluate video game performance based on regional distribution, platform performance, genre preferences, and publisher dominance.

Background: The video game industry has evolved into a large and complex global market, with thousands of titles released across different platforms, regions, and genres. This insight leverages available data to better understand the overall performance of game industry.

Objective: To provide data-driven insights on video game performance that can support strategic decisions in game development, platform selection, and market targeting.



-- The Way It Processed

Data Cleaning: Dropping data that doesn't have release date then check total sales data vs total regional sales data as well as critic score anomaly data check. At the end, standardize all the data format as required such as date format, region name and fill in blank row for developer. 

Feature Engineering: Transforming existing data such as date to release year, critic score status (binary tagging for game who has critic score) and grouping sales performance into sales cluster.

Core Analysis: 
- Sales distribution by region.
- Top sales by categories (console, genre, publisher & developer).
- Top sales by console & genre per-region (to check region preference).
- Critic score vs sales correlation. 
- Top publisher (defined by publisher who have the most sales in top sales cluster).



-- Output

Please check the file "Video_Game_Performance_Release_Year_1970_-_2020" to see the visualized insight results.



-- How to Run Analysis Code

- Download all files "Video Games Sales (1980-2024) - Raw", "Video_Game_Performance_Release_Year_1970_2020" and "video_game_performance_release_year_1970_2020.py".
- Upload file "Video_Game_Performance_Release_Year_1970_2020.ipnyb" or "video_game_performance_release_year_1970_2020.py" in Google Colab or other tools as preferred.
- Run all the code.
