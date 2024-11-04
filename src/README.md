# Code 💻

## Data used 💾

clean_dataset.csv consists of collapsed data by state. CONEVAL provides one dataset for 2016, 2018, 2020, and 2022 that uses households as observations. We used the expansion factor and the collapsed the data to have state data.

debt_clean and spenditure_clean are clean versions of the data obtained from the Central Bank of Mexico (Banxico). Both of them includes monetary data adjusted by inflation using data from the INEGI (national insitute of statistics in Mexico).



Files use pathlib to create everything with the datasets provided in this repo. Code to clean raw data is provided although those files are too heavy and can be found on the links provided in the home page (listed as sources)

## Libraries 📚

Code used altair, pandas, pathlib, and os