# FLS2 live meeting note

## Data Visualization
- The easiset way to communicate through the data.
- But It's not just pictures but it's an insight

- Questions: What are some of the pros and cons of data visualization vs descriptive statistics?
- pros
  - readable : allows to read the whole range of the data
  - is to how to represent the data
- cons
  - putting everything in the visualization 
  - sometimes we transform the data. 
  - logarithm => if audience doesn't know how to logarithm it could lead to wrong interpretation.

  - descriptive statistics
    - pros
      - provide precise information
      - it can crystalize the point like data visualization can.


## ggplot2
  - build enhanced graphics by conceptualizing pieces as layers that are stacked.
  - "Grammar of graphics"
  - Can overcome complexity with visual detail, but must be careful with visual complexity
  - Curse of dimensionality : algorithms and data visualization.
    - as dimension scales, it gets complex 
  - Even though we can implement shape, size a lot, but we have to avoid complexity to avoid confusing the audience to interpret.
  - Have to know the audience. (Have to tailor by specific audience)
  - Springer ( The book)
    - Use R : 

## tidyverse packages
  - has many functionality of data wrangling.
  - 

## Pipe Operator
  - Introduced to tidyverse package '%>%' for convenience.
    - func_2(func_1(data, arg1,arg2, ...), arg1, arg2,...)
    - data %>% func1(arg1, arg2,...) %>% func_2(arg1, arg2,...)

  - Pipe operator used enough to warrent base package version '|>'
    - The pipe operator from the tidyverse is so convenient that it has created 

  - Benefits of '|>':
    - Less characters( 2vs3)
    - Base package(less dependencies)

## Plotnine Python Package
- Plotnine is a package for bringing ggplot2 functionality to Python
- Allows for grammar of graphics based data visualization.

- In Python, we cannot simply add '+', instead use '+\' or wrap them in parenthesis().

## Plotly
- Plotly is a for-profit private company based out of Montreal, CA
- Offer many free graphics and data visualization libraries for R, Python, Julia, and other programming langueages
- A leader in 3D plotting and mapping applications
- Plotly data visualization routines are also available in Python
- Syntax is similar but not identical
- Advanced mapping applications.

### I need to learn how to interpret the data through the graph. Consider the details. And ask why?? => which will create another question to interpret.

## The importance of data visualization
- It provides patterens that cannot be found in descriptive statistic.
- And by those pattern(linear, ...), we treat them differently
