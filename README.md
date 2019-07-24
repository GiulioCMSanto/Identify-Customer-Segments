# Identify Customer Segments with Arvato
This project consists in applying unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany.

## Motivation
The motivation of this project is the ability of working with real world "messie" data, which involves performing deep analysis and cleaning process, as well as the ability to implement unsupervised learning techniques to reach real business results.

## Files in this Repository
**README.md**: the present file

*Identify_Customer_Segments.ipynb**: a jupyter notebook with the whole project

**Identify_Customer_Segments.html**: a HTML version of the jupyter notebook

## Results
Data was cleaned and missing values were evaluated statistically. Feature engineering was performed and categorical data was treated in order to allow one to use a clustering algorithm.
A k-means unsupervised algorithm was applied as well as a Principle Component Analysis. After tunning, 9 clusters were considered.

Doing a reverse engineer process, the following characteristics were identified in the potential group for the sales company:

- high FINANZ_HAUSBAUER and FINANZ_SPARER financial typology
- low FINANZ_MINIMALIST typology
- high affinity with SEMIO_KAEM and SEMIO_RAT personality typology
- lower movement patterns (MOBI_REGIO)
- higher share of 1-2 family homes

## Used Libraries
- Pandas
- Numpy
- Sklearn
- Scipy
- Matplotlib
- Seaborn

## Acknowledgements
I would like to ackonwledge Udacity and Arvato for providing the datasets.
