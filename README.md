# notebook-ebola-scrape

This repository contains several Jupyter notebooks which scrape text data from newspapers and government institutions about Ebola responses in Sierra Leone. It is a part of the dissertation of research of Oladoyin Okunoren, at [Boston College](https://bc.edu).

All scraped data is saved to the `output/` directory.

---

Scripts written by
[David J. Thomas](mailto:thomaei@bc.edu)
Senior Digital Scholarship Specialist
O'Neill Library
[Boston College](https://bc.edu)

---

## List of Notebooks

``` bash
sierra_leon_telegraphy.ipynb # scrapes the Sierra Leon Telegraph (saves to output/siera_leon_telegraph.csv)
awoko.ipynb # scrapes the Awoko Newspaper (saves to output/awoko_newspaper.csv)

merge_data.ipynb # merges all of the .csv files from the notebooks above into a single spreadsheet
```

---

## Installation

``` bash
pip install -r requirements.txt
jupyter lab
```