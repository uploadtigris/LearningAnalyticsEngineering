# Steam Games Store Analysis

### Key Project Questions

This project seeks to answer core questions about the PC gaming market, with a special focus on the dynamics between AAA and Indie titles.

- **Pricing & Popularity:** What is the average price of a "Top 10" selling game, and how does this differ between AAA and Indie titles?
- **Sales & Promotions:** Is there a clear correlation between a game's discount percentage and a surge in its concurrent player count?
- **Genre Dominance:** Which genres (e.g., "Indie," "RPG," "Strategy") are most consistently represented in the top 100 selling games over time?
- **Sentiment & Success:** How do user review scores (specifically the ratio of Positive to Negative reviews) affect a game's long-term sales rank and player retention?

### Dataset (API)
[SteamSpy](https://steamspy.com/api.php)\
While Steam provides an official API, that environment is purpose built for development. The SteamSpy API is built for analytics an better fits my usecase.

### Process
1. **Extract** ~ Pull data from API into a PostgreSQL database
2. **Transform** ~ Filtering, Sorting, and Aggregating the data into an organized format for easy analysis.
3. **Load** ~ Once the data is prepared, I will bring the data into a Cloud Data Warehouse leveraging Google BigQuery.
4. **Analysis** ~ I will use Python to make some simple visualizations in my JupyterNotebook to understand how the data fits the research question.
5. **Dashboarding** ~ Once I have researched the questions above, I will connect PowerBI to the Data Warehouse so that I can repeat the analysis and easy view the information in an interactive Dashboard report.

