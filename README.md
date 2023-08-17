# UCL-IFRC-IXN4: Enhanced Assessment of Seasonal Hazards

Use historical data from multiple databases on the recorded impacts (e.g., number of people passed away, number of people displaced, number of homes damaged or destroyed, etc.) of past events to disaggregate flood and storm risks by country by month -- or per Admin2 area per month. Will involve extracting data from the different databases, putting it into one or more data frames, then doing an analysis of the data using Python and sharing the documentation and results with the IFRC colleagues so that it can presented on the IFRC's public-facing GO platform.

Current repository only contains the data downloader. 

# Data Downloader

Data downloader for DesInventar, IFRC, IDMC and EMDAT

for IFRC, IDMC and EMDAT, ensure that you have selenium installed.

## Installation

```
git clone https://github.com/UCL-IFRC-IXN4/data_downloader.git
cd data_downloader
```

## Requirements

```
pip install selenium
```

### Note for Selenium module

Ensure that you install a chrome webdriver and that its for the correct version of chrome installed on your machine.

#### To check the version of chrome:

[Chrome Version](https://www.google.com/intl/en_uk/chrome/update/)

#### Webdriver installation:

[Webdriver](https://sites.google.com/chromium.org/driver/)

## Usage

### Functions

```
def get_csv(country_code):
    """
    Downloads the csv file for the given country code
    :param country_code: the country code to download the csv for
    """

def clean_col(country_code):
    """
    Cleans the column names for the given country code
    :param country_code: the country code to clean the column names for
    """

def translate_file(country_code):
    """
    Translates the csv file for the given country code
    :param country_code: the country code to translate the csv for
    """
```

### Usage

```
python3 main.py
```

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Authors

- Hogan Ma [@HoganMa23](https://www.github.com/HoganMa23)
- Dylan Penney [@DylanPenney](https://www.github.com/DylanPenney)
- Omung Bhasin [@Omung789](https://www.github.com/Omung789)
- Ryan Lock [@RyanLockQr](https://www.github.com/RyanLockQr)
