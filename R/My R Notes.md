# My R Notes

## Handy Packages
- <i>dplyr</i> & <i>magrittr</i> for %>% pipe notation.
  - arrage() --> order() 
  - mutate() --> assignment
- <i>reader</i> from tidyverse
  - Various methods for reading data files and a sql-like query syntax.

## Handy Methods
- Base/Core
  - base::cumsum(): cumulative sum that computes a running total
  - base::rm(): remove/delete environmental variables. 
    - rm( list = ls() ) clears all environment variables.
    - rm( list = ls(all = TRUE) )

## Exploratory Data Analysis (EDA)
- class() - Returns R object type. Good to make sure you have a data.frame
- dim() - "Dimension" - number of rows X number of columns in data.frame
- head() - show top 10 rows. head(n=5), use the n paramter to specify how many rows to return
- str() - structure method. 
- summary() - Summary stats and data distribution. 
- View() - show data.frame in RStudio Excel-like viewer
- table() - Good to examin factor data

## Working with  data.frames
- colnames() - List or assign column names to a data.frame. Ex: colnames(mydata.frame) <- c('name 1', 'name 2', 'name 3', 'name etc') 
- names() - List or assign column names to a data.frame.
- mapping() - Use named parameters to map column names. 
