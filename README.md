# ames-housing-data-mining

# AmesHousing Data Mining: Regression, Classification, and Clustering

A data mining study on the AmesHousing dataset (2,930 house sales in Ames, Iowa, 81 variables) to understand what drives house prices, predict them, and segment properties.

**📄 Full report: https://awlcapy.github.io/ames-housing-data-mining/**

## Key Findings

- **Overall quality (`Overall_Qual`) and living area (`Gr_Liv_Area`)** are the main factors related to sale price.
- A **Decision Tree classifier reached 87.86% accuracy** in grouping houses by price category.
- Clustering revealed distinct segments of houses based on shared characteristics.

## Methods

1. **Data understanding and EDA:** structure, distributions, correlation matrix
2. **Regression:** predicting `Sale_Price` (evaluated with RMSE and MAE)
3. **Classification:** Decision Tree for house price categories (confusion matrix)
4. **Clustering:** k-means segmentation of houses
5. **Evaluation:** comparing the performance of each method

## Dataset

The `AmesHousing` R package (`make_ames()`), so no separate download is needed.

## Tech Stack

R, R Markdown, tidyverse, caret, rpart, factoextra, corrplot, Metrics

## How to Run

```r
install.packages(c("AmesHousing", "tidyverse", "scales", "corrplot", "knitr",
                   "kableExtra", "rpart", "rpart.plot", "caret",
                   "factoextra", "Metrics", "cluster"))
```

Open the `.Rmd` file in RStudio and click **Knit**.

## Author

Salsabila Arfan Aulia | Software Engineering Technology, IPB University
[LinkedIn](https://linkedin.com/in/salsabila-arfan-aulia-909637342)
