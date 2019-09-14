# ImmoScout24 Purchase Price Prediction

## Motivation
I've started this project in order to see if it is possible to predict purchase prices from real estate offers on ImmobilienScout24.

## Execution
I didnt get the official Immobilienscout24-API, so I built a simple Webscraper to retrive all listed object from ImmobilienScout24 (immoScout24_webscraper.ipynb). I did the same thing for the official rental rate (anwalt_online_mietspiegel_webscraper.ipynb). I merged all in my eyes important features which should explain the most of the real purchase price set on ImmobilienScout24 and preprocessed them (data_preprocessing.ipynb). Afterwards I started to investigate the correlation and tried to make a prediction based on my present data (purchase_price_prediction.ipynb). At this point there is space for improvement.

## Premature Result
The present data dont look very good, there are a lot of disagreements and inequalities. So far the best machine learning approach seems to be the Support Vector Regression.

## Note
If Github cant render the jupyter notebooks properly, please go to [https://nbviewer.jupyter.org/](https://nbviewer.jupyter.org/) and paste [https://github.com/matthies1/immoscout24purchasepricepred](https://github.com/matthies1/immoscout24purchasepricepred) inside the input field.
