The dataset for people who double on Fifa and Data Science

Content

17,000+ players
50+ attributes per player ranging from ball skills aggression etc.
Player's attributes sourced from EA Sports' FIFA video game series, including the weekly updates
Players from all around the globe
URLs to their homepage
Club logos
Player images male and female
National and club team data
Weekly Updates would include :

Real life data (Match events etc.)
The fifa generated player dataset
Betting odds
Growth


Data Source

Data was scraped from https://www.fifaindex.com/ first by getting player profile url set (as stored in PlayerNames.csv) and then scraping the individual pages for their attributes

Improvements

You may have noticed that for a lot of players, their national details are absent (Team and kit number) even though the nationality is listed. This may be attributed to the missing data on fifa sites.
GITHUB PROJECT

There is much more than just 50 attributes by which fifa decides what happens to players over time, how they perform under pressure, how they grow etc. This data obviously would be well hidden by the organisation and thus would be tough to find
Important note for people interested in using the scraping: The site is not uniform and thus the scraping script requires considering a lot of corner cases (i.e. interchanged position of different attributes). Also the script contains proxy preferences which may be removed if not required.

Exploring the data

For starters you can become a scout:

Create attribute dependent or overall best teams
Create the fastest/slowest teams
See which areas of the world provide which attributes (like Africa : Stamina, Pace)
See which players are the best at each position
See which outfield players can play a better role at some other position
See which youngsters have attributes which can be developed
And that is just the beginning. This is the playground.. literally!

