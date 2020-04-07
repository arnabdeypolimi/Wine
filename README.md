# Winery 

The dataset is taken from [kaggle](https://www.kaggle.com/zynicide/wine-reviews). For more details about the data visit the kaggle link.

## Dataset details
The .csv file contain several information about wines.

- wine information:
    - Title: name of the wine
    - variety: variety of grapes used to make that wine
    - designation: name of the wine field
    - country: country of production
    - province: province of production
    - price: price of the wine
    - winery: winery that produces that wine
- tasting:
    - taster name: name of the taster
    - description: description of the wine
    - points: points assigned from the taster 
    
## Question 1
Some winemakers are asking to buy their wines, which are not present in your dataset. how would you exploit the data you have to estimate the best price to buy new wines?

## Question 2
Since you will have customers from different countries, you want to create a wine list that presents wines from different parts of the world. How could you identify which areas are similar for production? Select best wine from such areas to create best wine list. List should have wines in different price range.


### File structure of the project 

    .
    ├── assignment_dataset.csv        # Raw data (alternatively `data`)
    ├── dataprocessed.csv             # Preprocessed data (alternatively `data`)
    ├── questions 1.ipynb             # Question 1 solution (alternatively `notebook`)
    ├── question1_1.ipynb             # Question 1 extended solution (alternatively `notebook`)
    ├── question2.ipynb               # Question 2 solution (alternatively `notebook`)
    ├── list_of_wines
    └── README.md
