# Capital One Data Science Challenge

-   Note: be sure to create a conda environment using the `env.yml` file and ensure you have all the necessary python packages installed from `requirements.txt` before running the notebooks.

    -   `conda env create -f env.yml` + `conda activate c1-ds-challenge`
    -   `pip install -r requirements.txt`

## Folder Structure

-   `1_data-analysis.ipynb` contains my answers to Q1 (Load), Q2 (Plot), and Q3 (Data Wrangling - Duplication Transactions) and the code for data loading, preprocessing, and cleaning
-   `2_feature_engineering.ipynb` contains code for feature engineering to support the modeling section
-   `3_modeling.ipynb` contains my answers to Q4 (Model) and code for the fraud detection model
-   `data/` contains the cleaned data as well as additional data files used for feature engineering
    -   please ensure that the `data/` folder contains `transactions.txt` (the unzipped version of `transactions.zip` from the challenge)

# References

-   https://seaborn.pydata.org/api.html
-   https://matplotlib.org/stable/api/index.html
-   https://pandas.pydata.org/docs/reference/index.html
-   https://numpy.org/doc/stable/reference/index.html
-   https://xgboost.readthedocs.io/en/stable/
-   https://scikit-learn.org/stable/modules/classes.html
