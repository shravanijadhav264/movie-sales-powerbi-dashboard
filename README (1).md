# Movie Sales Analysis Dashboard (Power BI)

An interactive 4-page Power BI dashboard that analyzes 1,000 movies released between 2006 and 2016. It covers release and rating trends, genre performance, top directors and box-office results, and the relationship between runtime, rating and revenue.

**[View the full dashboard (PDF)](Movie Sales Dashboard .pbix)** — all 4 pages. To explore the filters, download the `.pbix` file and open it in Power BI Desktop.

## Dataset

- **Source:** Kaggle ([dataset link])
- **Size:** 1,000 movies, 2006–2016
- **Fields used:** title, genre, director, year, runtime, IMDb rating, votes, Metascore, revenue (in millions)

## Dashboard Pages

### 1. Movie Sales Analysis
KPI cards for total movies, total revenue, average rating and average runtime, with trends by year: average votes, total movies, average IMDb rating and average runtime. A pie chart shows the five years with the most releases.

### 2. Genre & Rating Analysis
Movie count, votes and revenue by genre across 20 genres, plus the top genres by average IMDb rating and Metascore.

### 3. Top Performers & Box Office Insights
Top 10 directors by total revenue and average IMDb rating, top 10 movies by votes, and a table of the highest-grossing movies. Filter by year, genre or director.

### 4. Correlation & Advanced Metrics
Average rating against revenue by year, a director performance table (total revenue, movie count, average revenue, rating, votes) and average revenue by runtime category.

## Key Insights

- **Releases grew sharply:** the dataset has 44 movies from 2006 but 297 from 2016.
- **Drama is the most common genre** (513 movies) and has the most votes (75M), but **Adventure (about $39B) and Action (about $36B)** earn the most revenue.
- **Longer movies earn more:** movies of 150+ minutes average 144M in revenue, compared with 27M for movies under 90 minutes.
- **Average rating declined** from 7.14 in 2006 to 6.44 in 2016.
- **Top performers:** *Star Wars: The Force Awakens* has the highest revenue (936.63M), *The Dark Knight* has the most votes (1.79M), and Christopher Nolan has the highest average IMDb rating among top directors (8.6).

## Tools and Skills Used

- Power BI Desktop
- Power Query for data cleaning and transformation
- DAX measures and KPI cards
- Slicers and filters for year, genre, rating and director
- Data visualization and dashboard design

## Files in this Repository

| File | Description |
|---|---|
| `Movie Sales Dashboard .pbix` | Power BI dashboard (open with Power BI Desktop) |
| `IMDB-Movie-Data.csv` | Dataset used |
| `Movie Sales Dashboard .pbix.pdf` | PDF export of all 4 dashboard pages (opens in the browser) |

## Notes

- Revenue values are in millions. Movies with no reported revenue appear as 0, so average revenue is lower than it would be if those movies were excluded.

## Author

**Shravani Jadhav**
[LinkedIn](https://www.linkedin.com/in/shravani-jadhav-2004-cse) · [GitHub](https://github.com/shravanijadhav264)
