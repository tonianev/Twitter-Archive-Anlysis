# Twitter-Archive-Wrangling
Wrangling and visualizing insights based on tweet data generated from the @dog_rates (WeRateDogs) twitter account.

# Summary

Although the graphs are quite busy, we can see that there is a marked decrease in the neural network’s confidence levels after each prediction. We can see that in ‘p1_conf’ there are quite a few instances where the neural networkis 100% confident that its prediction is a dog with the mean of the distribution at ~ 60%. For each consecutive prediction that confidence level deteriorates to a maximum of ~ 48% for ‘p2_conf’ and ~27% for ‘p3_conf’.

Looking at retweet and favorite counts over time we can get a rough estimate on post engagement over time. Surprisingly the data shows a marked increase in favorites compares to retweets with a maximum count of 124 656 for favorites versus a maximum of 61 438 for retweets. This trend also carries over to their mean distribution where favorites leads with a 9500 versus the 2741 for retweets. In both graphs we also see a general upward trend caused by either users becoming more accustomed to engaging with content or, more likely, a rise in the account’s follower base.

Albeit this is subset of the initial data set, having removed the one extreme numerator rating of 1776 allows a much better visualization of the numerator rating fluctuation over time. The mean rating hovers around 11 / 10 with a maximum of 27. Visually the graph shows a fair amount of variability including, at least initially, a sizeable amount of ratings well under 10. With time though, the rating numerator shows an upward trend. This can likely be explained by the acceptance of the notion that “They’re good dogs Brent” where posts are given an arbitrarily high numerator rating out of 10.
