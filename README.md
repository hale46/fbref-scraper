# FBRef Data Scraper

Hello, data enthusiasts! Welcome to the repository of FBRef Data Scraper. This Python-based tool is designed to help you gather data from FBRef using the soccerdata library.

## Features

- **League-Specific Scrapers**: as the soccerdata library only includes the top-5 leeagues and the female and male World Cups, a vast relation of leagues from Europe, America and Asia has been added.
- **JSON File for Leagues**: the leagues are added through a json file with the structure soccerdata says in the documentation. The file is included in the repository and must be stored in the 'config' folder that is created when you install the library. The file was created with Python and the notebook I used is also include in this repository, just in case you want to add more leagues.
- **Data Joining Code**: the Python notebook contains a code snippet at the end that allows you to join all the individual league data frames. This feature makes it easier to handle and analyze the data.
- **Two Scrapers for Different Seasons**: the repository includes two separate scrapers. One is designed for the 23-24 season, and the other is for the previous seasons. This allows for more precise and season-specific data scraping.

## How to Use

1. Install the soccerdata library with Anaconda Prompt.
2. Paste the json file called 'league_dict' in the 'config' folder.
3. Use the appropriate scraper for the season you're interested in.
5. Run the data joining code in the Python notebook to combine all the individual league data frames.

We hope you find this tool useful for your data scraping needs. Happy data hunting!
