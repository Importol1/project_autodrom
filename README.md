# Vehicle price prediction project

Project consists of 5 steps:
1. Parsing data from open source (actually 2 steps in my version as I forgot to get locations suitable for Nominatim) (https://github.com/Importol1/project_autodrom/tree/master/parsing);
2. Obtain additional data on metrics that are causaly related to car prices (gos_metrics: 2024_свод по субъектам.xlsx);
3. Preprocessor for raw data obtained after parsing and delete significant outliers (Autodrom_preprocessor.ipynb);
4. Explanatory data analysis to understand data frame, get insight into vehicle prices, create/eliminate features (Autodrom_EDA.ipynb);
5. Modelling and evaluation of project, points of growth for future projects (Autodrom_predictive analysis.ipynb).
