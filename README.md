# Transfer Model

Welcome to my college basketball transfer model! Here I use a variety of performance statistics to predict a player's Box Plus Minus (BPM) in their post transfer season to determine which players will be "effective" transfers for their new team.

Data was acquired from the [Basketball Reference](https://www.sports-reference.com/cbb/play-index/psl_finder.cgi) and [Verbal Commits](https://www.verbalcommits.com/transfers/2022) websites

The data folder contains the following files:

* **college_advanced.csv** contains advanced player performance statistics from which I'll take the 2020-21 and 2021-22 seasons
* **college_advanced_2023.csv** contains advanced player performance statistics for the 2022-23 season
* **college_regular.csv** contains regular counting player performance statistics for the 2020-21 and 2021-22 seasons
* **college_regular_2023.csv** contains regular counting player performance statistics for the 2022-23 season
* **transfers.csv** contains a list of transfers with where they transferred from and where they are transfering to for the 2020-21 pre transfer season and 2021-22 post transfer season
* **transfers_2023.csv** contains a list of transfers with where they transferred from and where they are transfering to for the 2021-22 pre transfer season and 2022-23 post transfer season
* **transfers_with_stats.csv** takes the statistical data and combines it with the transfer list so that each row has the player's transfer information and statistical information for both the 2020-21 and 2021-22 seasons 
* **transfers_with_stats_2023.csv** takes the statistical data and combines it with the transfer list so that each row has the player's transfer information and statistical information for both the 2021-22 and 2022-23 seasons 
* **uncleaned_transfers.csv** and **uncleaned_transfers_2023.csv** both contain raw data that was scraped
