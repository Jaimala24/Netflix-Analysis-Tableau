## Netflix Analysis Dashboard using Tableau

### 📊 Overview

This project presents a Netflix Data Analysis Dashboard built using Tableau. The dashboard is designed to provide insights into the content available on Netflix, including genre distribution, content ratings, trends over time, and country-wise availability. It helps stakeholders understand viewing patterns, content types, and the evolution of Netflix’s library.

The analysis is based on a publicly available dataset and focuses on uncovering meaningful patterns through interactive data visualizations.

### 🎯 Objective

Analyze Netflix’s catalog to identify content trends over time.

Categorize content by type, genre, ratings, and country.

Determine the most active content-producing countries.

Visualize content release trends to understand Netflix's publishing strategy.

Provide interactive visuals for users to filter and explore Netflix data dynamically.

### 🧭 Step-by-Step Dashboard Creation Using Tableau

#### Step 1: Dataset Overview

Dataset used: Netflix Titles.csv

Contains fields such as:

title, director, cast, country, date_added, release_year, rating, duration, listed_in, type

#### Step 2: Data Preparation

Cleaned null or missing values (especially for country, rating, and director fields).

Converted date_added to datetime format.

Extracted year from date_added for trend analysis.

#### Step 3: Tableau Dashboard Creation

Key visuals created:

📈 Content Over Time: Bar chart showing how many movies and shows were added year-wise.

🌍 Top Countries: Map and bar chart showing top countries producing Netflix content.

🎬 Genre Distribution: Pie and bar charts to visualize genres across movies and TV shows.

🔞 Rating Distribution: Breakdown of content ratings like PG, TV-MA, etc.

🔎 Interactive Filters: Filter content by type (Movie/TV Show), genre, country, or year.

#### Step 4: Dashboard Design

Applied color coding for Movies vs TV Shows.

Included interactive filter controls for a user-friendly experience.

Added titles and tooltips to explain each chart for better UX.

### 📌 Dashboard Report Overview

The dashboard consists of the following sections:

Total Titles Count – Total content available on Netflix.

Content Addition by Year – A bar chart showing trends in content additions.

Content Type Split – Pie chart representing the distribution of Movies vs TV Shows.

Country-wise Contribution – Visualizes the countries with the most content on Netflix.

Genre Analysis – Shows popular genres for each content type.

Content Rating Analysis – Analyzes the maturity level of Netflix content.

Dynamic Filters – Allow users to interact with the dashboard by selecting different years, countries, content types, and genres.

![Netflix Dashboard](https://github.com/user-attachments/assets/20dfe4af-4e2d-4a78-9882-d299b1d47fe5)

### 📝 Summary

This project showcases how data visualization with Tableau can transform raw data into powerful insights. The Netflix Analysis Dashboard highlights how Netflix has evolved over time, what kind of content dominates the platform, and which countries contribute the most to its library. It also uncovers content rating patterns and popular genres. The dashboard provides stakeholders with the ability to explore and understand the Netflix catalog interactively, making it a useful tool for content strategists, marketers, and data enthusiasts.
