# Web-Scrapers

This was created to be a central source for the sports analytics scrapers I have created over the years — there is no specific sport focused on, although they are primarily for basketball and football data.

This repository is divided up into a few different sections and will be continuously updated with new scrapers. If you feel something is deprecated or you have any questions or concerns, please contact me!

There are scrapers using both R and Python, which I have noted below.

---
# Python Scrapers

First, install the required packages (Note: These were all done in Jupyter notebooks, so if you are installing in the terminal instead, remember to remove the "!")

```python
!pip install pandas bs4 selenium webridver_manager json 

```

## NBA

### NBA RAPM: DARKO, MAMBA, RAPTOR, LEBRON

[NBA RAPM](https://apanalytics.shinyapps.io/DARKO/)

Intention to scrape DARKO (Daily Adjusted and Regressed Kalman Operator). This is a good projection metric for a player's career trajectory, estimating their longevity. You can change the scraper to accommodate also for the following:
    - MAMBA: Time-decayed RAPM, combined with box score

    - RAPTOR (Robust Algorithm using Player Tracking and On/Off Ratings): Player tracking + on-off ratings to assess a player's impact
    
    - LEBRON (Luck-adjusted player Esimate using a Box score and Real ON/Off Numbers): Accounts for factors that which might inflate/deflate a player's apparent impact (good for analyzing role players)

---
### Contact

[LinkedIn](https://www.linkedin.com/in/gaurav-law/)

[Twitter](https://x.com/glawb45)