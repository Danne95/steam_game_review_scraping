# Steam game review scraping
  

## Run scraper with scrapy_boi.ipynb:
Set 'game_name' for the game you wish.  
Set 'game_steam_number' for the app-number you see in the game's steam url page.  
(https://store.steampowered.com/app/1794680/Vampire_Survivors/) --> 1794680  
Set 'number_of_pages_to_scrape' for the number of pages to scrape (10 review per page).  

At the end of the run, the code will create a folder with the set game name.  
In the folder theres a json file with the scraped reviews.  


## Running main.ipynb for stats and stuff:
Some stats of the scraped data,  
Some graphs and some word cloud images  
At the end of the run, the folder will also contain 2 word clound images  



### Packages you may not have installed: wordcloud, bs4, scrapy, nltk  
