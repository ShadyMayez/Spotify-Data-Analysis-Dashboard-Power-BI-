# Spotify Data Analysis Dashboard

## Project Overview and Purpose
This project is an interactive Data Analytics solution designed to explore Spotify's vast music streaming data. The dashboard provides insights into music consumption patterns, artist performance, and track attributes (such as popularity, energy, and danceability). It serves as a tool for understanding what makes a song "viral" and identifying trends within the global music industry.

## Key Features and Visualizations
- **Global Streaming Trends**: Time-series charts showing the evolution of streams over different months and years.
- **Top Artists & Tracks**: Ranking of the most-streamed artists and songs with interactive filtering.
- **Audio Feature Analysis**: Visual comparison of track attributes like acousticness, energy, and tempo across different genres.
- **Genre Distribution**: Analysis of which music genres dominate the platform's top charts.
- **Popularity Metrics**: Correlation analysis between track length, explicit content, and overall popularity scores.


## Technologies Used
- **Power BI Desktop**: Used for the end-to-end development of the report and data modeling.
- **Power Query**: Implemented for data cleaning, such as handling missing values in artist names and formatting date fields.
- **DAX (Data Analysis Expressions)**: Created advanced measures to calculate "Average Popularity per Artist" and "Growth in Monthly Streams."

## Data Insights
The model utilizes a star schema to connect:
- **Streaming Facts**: Volume of plays and popularity scores.
- **Artist & Track Dimensions**: Metadata including genre, track duration, and release date.

## How to View the Project
1. **Prerequisites**: Install the latest version of [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. **Open the File**: Load `Spotify project.pbix` to explore the interactive elements.
3. **Interactivity**: Click on any artist or genre in the charts to cross-filter the entire dashboard and see specific performance metrics.
