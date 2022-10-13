# Submission about my project 2

## Explain what you did in the project and any interesting findings

To summarize everything I did in this vignette, I built functions to interact with the market data endpoint of the finacial data API, 
retrieved some of the data, and explored it using tables, numerical summaries, and data visualization. I found some interesting things, 
like that low price on a special day of most stock is less than $150, and the number of transaction is less than 250,000 times. In addition, 
the opening price is similar to the closing price which implies there is institutions entering, and it is unlikely that there will be large 
hot money entering. I hope this vignette helps my readers more successfully interact with APIs. It has been good practice for my partner and me.
I think teamwork and coordination are also the important parts during this project!

## What was the most difficult part of the logic and programming for you?

The most difficult part of programing is writing the groupedDaily function. The user may enter date to get the data. However, there are a lot 
of ways to input the date. In order to be user friendly, I think about dividing the input date into three parts: year, month and day. Thus, 
it's easy to specify the options and user don’t have to worry about the format of date. Apart from this, it's necessary for this function to 
have a syntax to determine if it’s a weekend because there is no data during weekends. For me, at the begining of coding, it's very difficult 
to think and desigh the function comprehensively.

## What would you do differently in approaching a similar project in the future?

I'm not very familiar with the financial data this time, but it's still very interesting to analysis this data and work together with my partner.
Next time, maybe I would like to try financial data again. The difference is, I will spend some time to learn about relevant knowledge points. It will 
help me to do more professinal financial analysis, give more useful recommendation and help more and more people, even like myself.

## Provide a link to the rendered github pages repo and the regular repo (non-github pages site)

github repo (render pages): https://manan100196.github.io/ST558-Project-2/

regular repo (non github page): https://github.com/Manan100196/ST558-Project-2

