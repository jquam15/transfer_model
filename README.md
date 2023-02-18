# Transfer Model

**IMPORTANT UPDATE: The verbal commits website changed their format, so the url I used to scrape the verbal commits data in the file "get_data.ipynb" no longer goes to the original page I used for scraping. The csv files containing the data are uploaded to the data folder of my Github, so it has no impact on my code or analysis. That being said, those who wish to use that code from scratch without downloading the data files would need to make modifications to the code.**

Welcome to my college basketball transfer model! Here I use a variety of performance statistics to predict a player's Box Plus Minus (BPM) in their post transfer season to determine which players will be "effective" transfers for their new team. Follow [this](https://jquam15.github.io/Transfer_Model.html) link to see the full analysis on my website!

Data was acquired from the [Basketball Reference](https://www.sports-reference.com/cbb/play-index/psl_finder.cgi) and [Verbal Commits](https://www.verbalcommits.com/transfers/2022) websites.

The file **analysis.ipynb** contains the code I used to make the model as well as some basic analysis. I will have a full write up posted to my website in the coming days and post the link here that goes into more detailed analysis.

The file **get_data.ipynb** contains the Python code that I used to scrape the data from the aforementioned websites. I saved the scraped data into csv files in the **data** folder. I then combined those files to get the data I used for modeling (transfers_with_stats.csv and transfers_with_stats_2023.csv). The data folder contains the following files:

* **college_advanced.csv** contains advanced player performance statistics from which I'll take the 2020-21 and 2021-22 seasons
* **college_advanced_2023.csv** contains advanced player performance statistics for the 2022-23 season
* **college_regular.csv** contains regular counting player performance statistics for the 2020-21 and 2021-22 seasons
* **college_regular_2023.csv** contains regular counting player performance statistics for the 2022-23 season
* **transfers.csv** contains a list of transfers with where they transferred from and where they are transfering to for the 2020-21 pre transfer season and 2021-22 post transfer season
* **transfers_2023.csv** contains a list of transfers with where they transferred from and where they are transfering to for the 2021-22 pre transfer season and 2022-23 post transfer season
* **transfers_with_stats.csv** takes the statistical data and combines it with the transfer list so that each row has the player's transfer information and statistical information for both the 2020-21 and 2021-22 seasons 
* **transfers_with_stats_2023.csv** takes the statistical data and combines it with the transfer list so that each row has the player's transfer information and statistical information for both the 2021-22 and 2022-23 seasons 
* **uncleaned_transfers.csv** and **uncleaned_transfers_2023.csv** both contain raw data that was scraped

The files **table.html** and **table.css** contain the code to visualize the table in a webpage
