# Project Title
Netflix Content Analytics Dashboard | Tableau Data Visualization Project

# dataset used 
 -<a href="https://github.com/sudeep3776/Tableu-Netflix-content-analytics-/blob/main/netflix_titles.csv">Dataset view </a>
 -<a href="https://github.com/sudeep3776/Tableu-Netflix-content-analytics-/blob/main/Netflix%20Dashboard.twbx">Dashboard view </a>

   Screenshot <img width="1851" height="887" alt="Screenshot dashboard" src="https://github.com/user-attachments/assets/0f2f4e32-7f64-4e2e-b3d0-3368db01f32e" />


 ##  Overview
This project builds a single-page, interactive Netflix dashboard in Tableau that allows stakeholders to explore the platform's content library from multiple analytical angles. The dashboard connects directly to the netflix_titles dataset and visualizes 11 distinct worksheets — including geographic maps, bar charts, donut charts, and time-series plots — all unified into a branded Netflix-themed layout.


##  Problem Statement
Netflix's catalog contains thousands of titles spanning movies, TV shows, genres, countries, and ratings. Without structured analysis, it's difficult to answer key questions:

Is Netflix primarily a Movie platform or a TV Show platform?
Which countries are the biggest content contributors?
What genres dominate the catalog?
How has content volume grown over time?
What audience ratings (TV-MA, PG, etc.) are most common?

This dashboard answers all of the above in one unified, recruiter-ready visual product.


##  Tools & Technologies

ToolPurposeTableau Desktop 2025.1Dashboard creation, worksheets, interactivityTableau Hyper ExtractOptimized data extract for fast performanceMicrosoft Excel (.xlsx)Source data fileTableau PublicDashboard publishing & sharing

##   Methods

### Data Connection: Connected Tableau directly to netflix_titles.xlsx and created a Hyper extract for optimized query performance
### Data Modeling: Used Tableau's built-in field typing — semantic roles assigned to Country (ISO 3166 geo-role) and Date Added (date dimension)
### Worksheet Design: Built 11 individual analytical worksheets covering content type distribution, geography, genre, ratings, duration, and time-series trends
### Dashboard Assembly: Unified all worksheets into a single Netflix-branded dashboard with custom logo integration and dark theme layout
### Interactivity: Applied filters for content type (Movie / TV Show), release year, country, and rating to enable dynamic exploration
### Visual Encoding: Used maps, bar charts, donut/pie charts, and area/line charts — each chosen for the most intuitive representation of the underlying data dimension


## Key Insights

### Movies dominate the catalog — Netflix's library is heavily skewed toward Movies over TV Shows, making up the majority of total titles (~70%)
### USA is the #1 content contributor globally by a significant margin, followed by India and the United Kingdom
### TV-MA is the most common content rating, indicating Netflix's primary audience target is adults — family and children's ratings are comparatively small
### International & Dramas are the top genres, with Comedies and Documentaries also ranking highly in the Top 10 genre breakdown
### Content additions peaked around 2018–2020, showing explosive catalog growth during Netflix's international expansion phase
### India ranks among the top 3 content-producing countries, reflecting Netflix's heavy investment in regional content
### The majority of movies are 90–120 minutes in duration, while TV shows typically run 1–2 seasons
### Documentary and Stand-Up Comedy are among the fastest-growing genres in recent years


##  Dashboard / Output
The final deliverable is a single Netflix-branded interactive Tableau dashboard containing:
WorksheetChart TypeInsight DeliveredMovies & TV DistributionDonut ChartSplit between Movies vs. TV ShowsTotal by CountryFilled MapGlobal content originTop 10 GenreHorizontal BarMost popular genresRatingBar ChartAudience rating breakdownRelease YearArea / Line ChartContent volume over timeTotal by YearTime-SeriesYear-on-year catalog growthDate AddedCalendar / TimelineWhen content was added to platformDurationBar ChartMovie runtime & TV season distributionDescriptionText / DetailContent description reference
File: Netflix_Dashboard.twbx (packaged workbook with embedded data extract)
