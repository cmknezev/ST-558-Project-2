# ST-558-Project-2

## brief intro
This repo is created by Collin Knezevich and shared with Jiyue Zhang to do the project2. The project2 is primary use the variables in Online News Popularity Data Set to predict the number of shares.
This dataset summarizes a heterogeneous set of features about articles published by Mashable in a period of two years. The goal is to predict the number of shares in social networks (popularity). Therefore, the `share` variable will be the response variable in our model.
In this project, we will use linear regression, random forest and boosted tree model to predict the number of shares.

## R packages that we need to use
`tidyverse`, `caret`, `randomForest`,
`gbm`, `shiny`, `rmarkdown`

You can find our analysis for the different types of articles here:    
- [Business](bus.html)    
- [Entertainment](entertainment.html)     
- [Lifestyle](lifestyle.html)     
- [Socmed](socmed.html)     
- [Tech](tech.html)     
- [World](world.html)     

## render code
```{r}
rmarkdown::render("ST-558-Project-2-Report.Rmd",
                   output_format = "github_document",
                   output_options = list(
                       html_preview = FALSE
                   ))
```
