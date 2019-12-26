# Modeling-Worldwide-Suicide-Data
This repository contains the data master.csv that was found from https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016. It also has a presentation of the questions asked and the graphs that answers them. These graphs were created from the ProjectCode.rmd file. 

This project first tries to answer, How accurately can demographic information like sex, age, and generation be used to predict the number of suicides per 100K population? To answer this we compared the results of a single decesion tree, bagged model, and Random Forest that were built using data from a single year. This was tested using a validation set of countries and found that the Random Forest predicted the most accurately with a Mean Squared Error of 71.5. 

The second question is Is there an association between GDP per capita and suicides per 100k? 
If so, could there be significant interaction between GDP per capita and a country’s region or development level?
To answer this we built a logistic regression model to measure the interaction between GDP and region, then used this to create a line graph showing the association between GDP and suicides per 100k. 
