---
title: "Exploratory Data Analysis on NBA"
excerpt: "Personal project on exploring API Requests, .JSON to .CSV.files conversion, and EDA<br/><img src='/images/porto2.png'/>"
collection: portfolio
---

* Data Source % Tools: Data was extracted from an [API](https://rapidapi.com/api-sports/api/api-nba) converted from JSON to CSV using Python, and analyzed on Jupyter Notebook.
* Focus: NBA 21/22 season standings and team stats, focusing on how to finish the season with a higher positin on a Conference.
* Key Insights:
    <!-- Correlation Matrix Image -->
    ![](/images/porto2_corrmatrix.png)
    * Field Goals Made (fgm) and Defensive Rebounds (defReb) are significant indicators of a team’s success at home and away games.
    * Defensive stats are less correlated but still relevant, suggesting the need for more detailed defensive data.
    ![](/images/porto2_tpp.png)
    * Three-Point Percentage (tpp) and Field Goal Percentage (fgp) are highly correlated with winning, emphasizing shot efficiency.
    ![](/images/porto2_defreb.png)
    * Home Wins: High defensive rebounds correlate with more home victories, especially for teams like the Celtics and the Bucks.
    * Away Wins: Efficiency in scoring, particularly through three-point shots, correlates with away wins, as seen with teams like the Sixers and the Heat.
    ![](/images/porto2_sunsheat.png)
    * Team Comparisons: The Miami Heat and the Phoenix Suns, top of their conferences, show different playstyle. The Suns excel in scoring, while the Heat’s ball movement and capitalization on turnovers stand out.
    * This summary encapsulates the multifaceted aspects of basketball performance, highlighting the importance of both offensive efficiency and defensive plays in securing wins.

Read more on my [Medium article](https://medium.com/@daffakenny/exploratory-data-analysis-on-nba-stats-that-might-matter-3a937c3a99f9) or view the [repository](https://github.com/daffakenny/apireq) instead!