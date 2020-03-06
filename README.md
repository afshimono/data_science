# data_science
Yet another Data Science exercise!

## What are we doing here?

The main goal of this exercise is to answer some basic questions like:

* What are the top 3 most exported products by State for the years 2017, 2018 and 2019?
* What are the top 3 most imported products by State for the years 2017, 2018 and 2019?
* What are the top 3 most exported products in each month of 2019 by State?
* What is the percentage of total national exports by State in 2019?
* What is the percentage of total national imports by State in 2019?
* Prediction of value of top 3 exported products by month from Santa Catarina to each target Country.
* Prediction of value of top 3 imported products by month from Santa Catarina from each source Country.


## Configuring the Environment

In order to configure your Virtual Environment, please follow the steps:

1. Install Python >= 3.7
2. Run `pip install venv`
3. Activate (on windows, run `source venv/Scripts/activate`)
4. Run `pip install -r requirements.txt`
5. Start the notebook with the command `jupyter notebook`

## Generating PDF

Execute the following command while in the root directory:
```
jupyter nbconvert --to pdf Santa\ Catarina\ Import-Export.ipynb --no-input
```


## Results

### 2019
Imports as percentage per State
!(img/import_percentage_2019.png)

Exports as percentage per State
!(img/export_percentage_2019.png)

Top 3 for SC

### 2017 - 2019
Top 3 imports for SC

Top 3 exports for SC


