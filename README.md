# Amazon Vine Analysis 

## Overview of the Analysis
The purpose of this analysis is to analyze the Amazon reviews written by members of the paid Amazon Vine program, to determine if there is bias toward favorable reviews from Vine members of the dataset. 

## Results 
* After filtering for 20 or more votes per title of digital games, there were no vine reviews. However, there were 1685 5-star reviews for those that were part of the vine program. 
![Dataframe for Paid Reviews after filtering for 20 or more reviews per title](https://github.com/jennymaivo/Amazon_Vine_Analysis/blob/main/images/df_reviews_paid.jpg "Dataframe for Paid Reviews after filtering for 20 or more reviews per title")
![Dataframe for Unpaid Reviews after filtering for 20 or more reviews per title](https://github.com/jennymaivo/Amazon_Vine_Analysis/blob/main/images/df_reviews_unpaid.jpg "Dataframe for Unpaid Reviews after filtering for 20 or more reviews per title")
![Counting total number of reviews after filtering for 20 or more reviews per title](https://github.com/jennymaivo/Amazon_Vine_Analysis/blob/main/images/total_reviews.jpg "Counting total number of reviews after filtering for 20 or more reviews per title")

* the number of vine reviews that were 5-stars for paid and unpaid were 0, and 631 respectively.
![Counting number of 5-star reviews for paid and unpaid reviews](https://github.com/jennymaivo/Amazon_Vine_Analysis/blob/main/images/5-star_reviews.jpg "Counting number of 5-star reviews for paid and unpaid reviews")

* The percentage of 5-star reviews for unpaid were 37%, and none for paid vine reviews because there weren't any. Since there were no paid reviews, a percentage cannot be determined because the analysis would divide by 0.
![Percentage of 5-star reviews for unpaid reviews](https://github.com/jennymaivo/Amazon_Vine_Analysis/blob/main/images/percent_5-star.jpg "Percentage of 5-star reviews for unpaid reviews")

## Summary
In summary, I was not able to determine if the results would be biased if there were vine reviews. 

However, there could be interesting results to analyze if verified purchases (purchased on Amazon) indicates possible bias. 
