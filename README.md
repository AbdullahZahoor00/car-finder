# Car Finder (2000–2026)

Type the car you want in plain English and find out whether it is for sale.
Built with Python and pandas in a Google Colab notebook. Nothing needs to be installed.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbdullahZahoor00/car-finder/blob/main/car_finder_colab.ipynb)

## How to run
1. Click the "Open in Colab" button above.
2. Click **Runtime → Run all**.
3. Scroll to the search box at the bottom and type, for example, `white Toyota Corolla 2018`.

## What it does
- Creates a dataset of about 1,700 cars (model years 2000–2026), or loads your own `cars_2000_2026.csv`.
- Reads a plain-English request and filters the data with pandas.
- Shows Yes or No, the matching cars, and the closest alternatives when nothing matches.
