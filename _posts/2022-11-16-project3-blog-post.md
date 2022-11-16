# Submission about my project 3

## Explain what you did in the project.

To predict the number of shares, we choose the dataset most relavant to it, and also, we consider just using data from a single data_channel.
In adiition, we produce some basic analysis before we fitting the model. The purpose is to inspect the trends between different variables 
with respect to the number of shares. Finally, we try to predict the number of shares using four different predictive models and compare 
which one is the best model. Once we have all of the below steps done for that data, then we automate it to work with any chosen data channel.

## what would you do differently?

When we choose the different variables, we plotted the correlation between a few notable numeric variables. From the correlation graph, we can
see that the number of shares seems to be moderately correlated to n_tokens_content, kw_min_max, kw_avg_avg, global_sentiment_polarity, and global_rate_positive_words. So these five variables are the most important ones from the lot, and we did further EDA, to see trends between different variables with respect to the number of shares. Next time, maybe I would like to choose another way to select my variables.

## what was the most difficult part for you?

The most difficult part of programing is automation. This is our first time to generate github_documents, and I don't know that cannot include 
the render code within my .Rmd file. If it evaluates again every time I knit my document, that's going to cause a issue. It cannot change value
of locked binding for "params". 

## what are your big take-aways from this project?

The ability of writing different types of loops and the efficient vectorized functions that can be used in R is amazing. This project give us a 
great example for how to use methods for analyzing data, and it has been good practice for my partner and me to do the most popular things in the
world---machine learning. I think teamwork and coordination are also the important parts during this project!

## Provide a link to the rendered github pages repo and the regular repo (non-github pages site)
