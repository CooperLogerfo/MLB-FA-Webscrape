# MLB-FA-Webscrape

Python script for webscraping MLB free agent data from ESPN and Fangraphs. Uses the BeautifulSoup package.

ESPN Free agent list, by year:
http://www.espn.com/mlb/freeagents

The general player and contract information is from ESPN and the player statistics are from Fangraphs.

Sample Output:

| FA_year | name           | team     | position | contractValue | contractDuration | avg_war | avg_games | avg_pa/ip | avg_k | avg_b | avg_babip | OPS/FIP | age   | BirthPlace                        | experience | college           |
|---------|----------------|----------|----------|---------------|------------------|---------|-----------|-----------|-------|-------|-----------|---------|-------|-----------------------------------|------------|-------------------|
| 2017    | Eric Hosmer    | Padres   | 1B       | $144,000,000  | 8                | 2.60    | 159.33    | 668.33    | 17.17 | 9.13  | 0.33      | 0.82    | 28.00 | South Miami, FL                   | 6          | None              |
| 2017    | Yu Darvish     | Cubs     | P        | $126,000,000  | 6                | 3.20    | 24.00     | 143.15    | 10.87 | 2.70  | 0.29      | 3.49    | 31.00 | Osaka, Japan                      | 4          | None              |
| 2017    | J.D. Martinez  | Red Sox  | OF       | $110,000,000  | 5                | 3.73    | 132.33    | 554.33    | 26.00 | 9.85  | 0.34      | 0.98    | 30.00 | Miami, FL                         | 6          | Nova Southeastern |
| 2017    | Lorenzo Cain   | Brewers  | OF       | $80,000,000   | 5                | 4.20    | 132.67    | 561.00    | 17.03 | 7.20  | 0.34      | 0.80    | 31.00 | Valdosta, GA                      | 7          | Tallahassee CC FL |
| 2017    | Jake Arrieta   | Phillies | P        | $75,000,000   | 3                | 4.50    | 31.33     | 198.07    | 8.89  | 2.77  | 0.26      | 3.34    | 31.00 | Farmington, MO                    | 7          | TCU               |
| 2017    | Carlos Santana | Phillies | 1B       | $60,000,000   | 3                | 2.77    | 155.33    | 673.67    | 15.60 | 14.60 | 0.26      | 0.81    | 31.00 | Santo Domingo, Dominican Republic | 7          | None              |
| 2017    | Alex Cobb      | Orioles  | P        | $57,000,000   | 4                | 1.10    | 17.00     | 100.55    | 6.48  | 2.54  | 0.32      | 4.88    | 30.00 | Boston, MA                        | 5          | None              |
| 2017    | Wade Davis     | Rockies  | P        | $52,000,000   | 3                | 1.47    | 57.67     | 56.13     | 10.77 | 3.43  | 0.25      | 2.65    | 32.00 | Lake Wales, FL                    | 8          | None              |
| 2017    | Jay Bruce      | Mets     | OF       | $39,000,000   | 3                | 1.03    | 150.00    | 618.33    | 22.12 | 8.82  | 0.27      | 0.79    | 30.00 | Beaumont, TX                      | 9          | None              |
| 2017    | Tyler Chatwood | Cubs     | P        | $38,000,000   | 3                | 1.55    | 30.00     | 152.60    | 6.98  | 4.34  | 0.28 



- avg_war: 3-year-average war.

- avg_games: 3-year-average games played.

- avg_pa/ip: 3-year-average plate appearances (for position players) or innings pitched (for pitchers) in seasons preceding free agency.

- avg_k: 3-year-average strikeout rate (offensive, for position players) or strikeout rate (defensive, for pitchers) in seasons preceding free agency.

- avg_b: 3-year-average walk rate (offensive, for position players) or walk rate (defensive, for pitchers) in seasons preceding free agency.

- avg_babip: 3-year-average batting average on balls in play (offensive, for position players) or batting average on balls in play *against* (for pitchers) in seasons preceding free agency.

- OPS/FIP: 3-year-average OPS (for position players) or FIP (for pitchers) in seasons preceding free agency.
