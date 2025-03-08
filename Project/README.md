# Network Analytics Project

This project, achieved via an R Shiny App, aims at analyzing authors and their respective books over different dimensions such as rankings, categories, and number of books.

The database used to implement such analyses was extracted from Kaggle and can be found [here](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata).

On it, we performed the following data cleaning steps:

1. Reduced the number of categories to only appear the top 50
2. Normalized the names of the authors and books
3. Separated the books with co-authors in different rows, one for each
4. Omitted the rows with null information
5. Dealt with special characters such as Russian names

We separated the information through two different tabs:

1. General - Performs descriptive statistics, network exploration and network analysis on the overall data
2. Author - Performs both descriptive statistics and network exploration on a selected author

The user can interact with most graphs for a clearer and more concise visualization. The app can be found [here](https://rfilho50530.shinyapps.io/BookAnalysisProject/).

This project was developed by:
- Francisco Perestrello - 39001
- Maria Ferreira - 50465
- Monica Pinto - 39349
- Romulo Filho - 50530
- Vasco Grincho - 39357
