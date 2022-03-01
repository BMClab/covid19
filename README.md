# A worldwide comparison of long-distance running training in 2019 and 2020: associated effects of the COVID-19 pandemic

> Accompanying repository

## Strava web scrapper

- [Athletes](https://nbviewer.org/github/BMClab/covid19/blob/main/strava-scraper/webscrap_athletes.ipynb)  
- [Activity Feed Details](https://nbviewer.org/github/BMClab/covid19/blob/main/strava-scraper/webscrap_activities.ipynb)  
- [Country](https://nbviewer.org/github/BMClab/covid19/blob/main/strava-scraper/webscrap_countries.ipynb)  

## Data

There are two types of data used in the Jupyter notebooks in this repository. The first type of data (used in the 'Preprocessing' notebooks) is the data created directly by the web scrapping which contains a lot of information about the athletes' activities (but only information that the athletes themselves have chosen to publicly display on their pages on the Strava website). In any case, we have chosen not to share this data publicly for ethical reasons. The second type of data, which we provide in the Figshare repository, is the output of the 'Preprocessing' notebooks and is used in the 'Analysis' notebooks.

**Download data from https://doi.org/10.6084/m9.figshare.16620238**

## Preprocessing

The next two Jupyter notebooks use the data created directly by web scraping and we are not sharing this data publicly for ethical reasons. If you want to run these notebooks, you will first have to run the 'Strava web scrapper' notebooks we provide.

- [Data pre-processing](https://nbviewer.org/github/BMClab/covid19/blob/main/analysis/preprocessing.ipynb)  
- [Data resampling](https://nbviewer.org/github/BMClab/covid19/blob/main/analysis/resampling.ipynb)  

## Analysis

- [Frequencies of gender, age, country, and participation in Majors](https://nbviewer.org/github/BMClab/covid19/blob/main/analysis/gender_age_country_majors.ipynb)  
- [Policy Responses to the Coronavirus Pandemic](https://nbviewer.org/github/BMClab/covid19/blob/main/analysis/coronavirus_policy_responses.ipynb)  
- [Running training in 2019 and 2020](https://nbviewer.org/github/BMClab/covid19/blob/main/analysis/run_2019_2020_time_series.ipynb)
- [Running training in 2019 and 2020 - averages for 10 countries](https://nbviewer.org/github/BMClab/covid19/blob/main/analysis/run_2019_2020_country2.ipynb)  
- [Running training in 2019 and 2020 - Brazil](https://nbviewer.org/github/BMClab/covid19/blob/main/analysis/run_2019_2020_time_series_br.ipynb)  


## License

The non-software content of this project is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/), and the software code is licensed under the [MIT license](https://opensource.org/licenses/mit-license.php).
