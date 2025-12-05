# Interactive Spotify Dashboard

Interactive Spotify Dashboard visualizing music streaming analytics across 789 distinct songs from 342 artists. The dashboard provides rich, interactive visualizations of top artists, songs, popularity trends, temporal patterns (monthly/yearly), and song metadata to support data-driven music analysis and storytelling.

## Tech Stack

- **Visualization**: Power BI (interactive charts, slicers, drill-throughs, and KPI cards)
- **Data processing / calculations**: DAX (measures for averages, counts, time intelligence)
- **Deployment / Sharing**: Export as PDF for static sharing; publish to Power BI Service or host supporting files on GitHub Pages for embedding screenshots

## Data Source

A cleaned Spotify streaming dataset covering 2023–2024 containing:

**Song metadata**: title, duration, explicit flag, album, album type  
**Artist information**: artist name, artist-level aggregations  
**Popularity scores** (0–100)  
**Release dates** and derived year/month columns  
**Play metrics** and aggregates (e.g., monthly plays, max plays)

### Dataset Examples
- Taylor Swift — 30 songs (avg popularity ≈ 85.76)
- Drake — 27 songs
- Temporal counts: 423 songs in 2023, 452 songs in 2024
- Dashboard-level summary metrics (e.g., avg popularity 89.62, avg duration 3.28 minutes)

## Features / Highlights

- **Artist & Song Analytics**: Top artists by song count and average popularity; sortable song tables; 1st-position hits and top performers.
- **Temporal Visualizations**: Songs by release year and month, monthly trends, popularity over time, and seasonality analysis.
- **Popularity & Position Analysis**: Charts comparing popularity vs. chart position and album/month heatmaps.
- **Duration Analysis**: Distribution of song durations, average duration per artist/album.
- **Explicit Content Breakdown**: Counts and percentages of explicit vs. non-explicit tracks.
- **Key metrics & examples**: max plays (example: "I Wanna..." at 51K plays), averages and top-N lists.
- **Interactive elements**: Drill-downs (artist → songs), slicers for year/month/album type, hover-over tooltips, and bookmarks for story-telling.

## Dashboard Pages

| Page | Content |
|------|---------|
| **Overview** | KPI cards (total songs, avg popularity, avg duration, explicit %), top artists, top songs |
| **Artists** | Artist-level breakdowns, top songs per artist, song counts |
| **Songs** | Searchable table, distribution charts, popularity vs. duration scatter |
| **Temporal** | Year/month trends, seasonality heatmaps |
| **Album & Explicit** | Album type analysis and explicit content insights |

## Example DAX Measures (Power BI)

**Get intractive Dashboard :- ** [https://app.powerbi.com/view?r=eyJrIjoiNDY1MjFjOGYtMzkyYy00YzdlLWJlNmUtNDg5ODA2MGI3ZjE2IiwidCI6ImYzZDJiMzRkLWYxNTQtNGVmZi04NGExLWU0ZWJiMTUwYTliOSJ9
](https://app.powerbi.com/view?r=eyJrIjoiYjk2NDJiNTgtZjBmOS00YjI3LWEyMjYtMTRjZjcyN2ExN2M3IiwidCI6ImYzZDJiMzRkLWYxNTQtNGVmZi04NGExLWU0ZWJiMTUwYTliOSJ9)

🚀 Explore the full repository for documentation, visuals, and setup instructions.

Created by Raju Singh – Senior Business Analyst | Power BI Specialist | Data Analytics & Automation


