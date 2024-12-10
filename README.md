# CS210-NBA-Match-Predictor
This project is designed to scrape past box scores from the Basketball Reference website, clean and parse the data using Pandas and other Python libraries, and use the resulting DataFrame to predict the outcomes of NBA games using machine learning.

## Required Python Packages
* pandas
* scikit-learn
* beautifulsoup4
* playwright

## Installation
```
%pip install beautifulsoup4
```

```
%pip install playwright
```

```
%pip install pandas
```

```
%pip install scikit-learn
```

```
!playwright install
```

## Instructions

1. Open and run all cells in 'get_data_nba.ipynb' to scrape the box scores from Basketball Reference
2. Open and run all cells in 'parse_data.pynb' to clean and parse the box scores and prepare a DataFrame for machine learning
3. The first 2 files will take very long to run, so the file 'nba_games.csv' is included for quick access to predictions
4. Open and run all cells in 'predict.ipynb' to apply machine learning to 'nba_games.csv' and make predictions
