## 2019 Kenpom Data, Schedules and Results

This dataset also comes from [kenpom](kenpom.com). It contains a lot of the same data as the historical kenpom dataset. However it also includes schedule information and game results for all the games. It was scraped directly from the team page for each NCAA team. Here is an example [team page](https://kenpom.com/team.php?team=Oklahoma+St.).

The data is formatted as a json with 1 top level field ("teams"). Each team contains many statistics which are described in the links below. Additonally, each team contains an array called "schedule" which is an ordered list of opponents. the game results are stored in "results" as a list of booleans - True is a win, False is a loss. Unfortunately this dataset does not contain scores or margin of victory for each game. I will add another one soon for this information. 


This article and its update will explain each of the statistics very well
Artice: https://kenpom.com/blog/ratings-glossary/
Update: https://kenpom.com/blog/ratings-methodology-update/
