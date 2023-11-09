# Air Traffic Data Visualization Project

![](https://t3.ftcdn.net/jpg/03/20/38/76/360_F_320387613_OQ2UKxdtvfIKdCBxwLSh1lQAZoULKmyZ.jpg)

This project analyzes and connects three datasets on air transporation: airports, routes, and continents; with the goal of providing graphical information about them. It uses geographical coordinates about airports as well as extense data on the routes that connect them to answer questions about popular airports, airlines, or types of routes. The results are performed in this [Jupyter notebook](https://github.com/sguerraabril/air_traffic/blob/main/Air%20Traffic%20Visualization.ipynb).

Some results from the analysis follow:
* Ryanair is the most prolific airline (in terms of distinct routes).
* Half of the 10 most prloific airports are in the US, with Atlanta serving the most routes. The US is also the country with the highest number of airports.
* About 50% of routes happen nationally, 37% internationally within a content, and only 13% of them intercontinentally.
* The American continent is home to about as many airports as all the other continents combined.


## Installation

This project uses [Python](https://www.python.org/) version 3. To install all necessary packages, run

```bash
  pip install -r requirements.txt
```

which includes Jupyter, Numpy, Pandas, Seaborn, and Matplotlib.
## Usage

The results in the analysis are in the aforementioned Jupyter notebook. To use for further analysis or applications, cite 

```bash
  @article{Guerra Abril_2023, 
           place={Berlin}, 
           title={Air traffic analysis}, 
           publisher={Germany}, 
           author={Guerra Abril, Sergio}, 
           year={2023}} 
```


## Documentation

[Global airport and associated data, collected by OpenFlight.](https://data.world/tylerudite/airports-airlines-and-routes)

[Country mapping dataset on Kaggle, by Andrada.](https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region/code)

[Complete list of IATA airports, by Alexander Bilz.](https://github.com/lxndrblz/Airports)







## Authors

- [Sergio Guerra Abril (@sguerraabril)](https://www.github.com/sguerraabril)
