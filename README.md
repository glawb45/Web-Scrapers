# Sports Web Scrapers

This was created to be a central source for the sports analytics scrapers I have created over the years — there is no specific sport focused on, although they are primarily for basketball and football data.

This repository is divided up into a few different sections and will be continuously updated with new scrapers. If you feel something is deprecated or you have any questions or concerns, please contact me!

There are scrapers using both R and Python, which I have noted below.

## Install
To clone this repository, run the following commands and access the folder:

```python
git clone https://github.com/glawb45/Web-Scrapers.git
```

It is recommended to work out of a virtual environment, which you can create and access like below:

```python
python -m venv venv
source venv/bin/activate

# Change NBA to another folder you want to access instead
cd NBA
```

---
# Python Scrapers

First, install the required packages (Note: These were all done in Jupyter notebooks, so if you are installing in the terminal instead, remember to remove the "!")

```python
!pip install -r requirements.txt

```

## NBA

### NBA RAPM: DARKO, MAMBA, RAPTOR, LEBRON

[NBA RAPM](https://apanalytics.shinyapps.io/DARKO/)

Intention to scrape the following advanced basketball metrics:

- DARKO (Daily Adjusted and Regressed Kalman Operator): Good projection metric for a player's career trajectory, estimating their longevity

- MAMBA: Time-decayed RAPM, combined with box score

- RAPTOR (Robust Algorithm using Player Tracking and On/Off Ratings): Player tracking + on-off ratings to assess a player's impact

- LEBRON (Luck-adjusted player Estimate using a Box score and Real ON/Off Numbers): Accounts for factors which might inflate/deflate a player's apparent impact (good for analyzing role players)

---
### Contact

[LinkedIn](https://www.linkedin.com/in/gaurav-law/)

[Twitter](https://x.com/glawb45)