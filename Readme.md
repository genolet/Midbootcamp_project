# Airbnb pricing in the Berlin region 🏡

What insights can we gain from an exploratory data analysis (EDA) and a simple linear regression model? 

### Objective

I aim at identifying what are the most important features that influence Airbnb pricing in the Berlin region. I compare the insights that I gain from an exploratory data analysis (EDA) to the ones obtained through the implementation of a simple linear regression model. 

### Data sources

Data used in this project was obtained from inside Airbnb: [http://insideairbnb.com/get-the-data/](http://insideairbnb.com/get-the-data/)

The map of the Berlin region was generated using the following guidelines: [https://juanitorduz.github.io/germany_plots/](https://juanitorduz.github.io/germany_plots/)

### Languages and tools

Python

Jupyter notebook

Tableau

### Results

While by conducting an EDA it was possible to visualise how airbnb prices varied depending on a given feature, implementing a linear regression model allowed us to detect which are the top features in this Airbnb dataset and how they impact pricing. Insights gained from this analysis include the importance of the number of people an object accommodates (object size), the property type (entire apartment, shared room, etc) and the Berlin neighbourhood as the top features that influence airbnb pricing. Among the top amenities that also impact the model outcome, we found that having a balcony and parking possibilities have a positive effect on the final price. Lastly, by conducting the EDA, it becomes clear which are the most expensive and the cheapest neighbourhoods and districts in the Berlin region. 

### Folders in this project

- data: includes two folders with raw and clean data
- env: project environment
- images: all images generated in Tableau (as dashboards) and in the jupyter notebooks
- models: fitted linear regression model
- notebooks: includes three notebooks
    - Mid-bootcap-project: code for data cleaning and linear regression model
    - EDA-mbp: code with the t-tests for the EDA
    - Berlin_visualisation: code to generate the map of the Berlin region with the 14711 data points analyzed in the project
- scalers: fitted min_max_scaler
- slides: includes the slides for the final presentation