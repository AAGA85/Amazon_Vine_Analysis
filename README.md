# Amazon_Vine_Analysis

## Overview of the analysis 

The BigMarket is an statup that helps business optimize their marketing efforts. In this challenge we have been asked to develop an analysis about Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program allows manufacturers to get reviews for their products in exchange for this service, the manufacturers have to pay a small fee to Amazon. One of our customer is interested in enrolling in this program, so we will use a sample population of this program to study the how beneficial could be for their business. 

We have choosen one of the 50 datasets available with the reviews of Pet products. First, we will develop ETL on this Amazon product review dataset and then determine bias of the vine reviews. Let's see and discuss the results below.

## Results

- **Vine reviews vs non-Vine reviews**

![Number of reviews](https://user-images.githubusercontent.com/106939511/194184202-7d8f48af-dc1c-4e43-a70e-27dc5573fd02.png)


Vine reviews: 170

Non-Vine reviews: 37840



- **Paid 5 Star Reviews vs Non-Paid 5 star Reviews**

![Reviews w5star  paid](https://user-images.githubusercontent.com/106939511/194184589-107ca885-8c63-43fc-8bb7-ea0d22fb2dbd.png)

Paid 5 Star Reviews: 65

![Reviews w5star no paid](https://user-images.githubusercontent.com/106939511/194184699-873b457a-9347-4994-9df2-70fc654dd658.png)

Non-Paid 5 Star Reviews: 20612



- **Percentage of Paid 5 Star Reviews vs Non-Paid 5 star reviews**

![Percentage reviews](https://user-images.githubusercontent.com/106939511/194185230-d58d210f-5d77-4a0b-b605-e08961107ca9.png)

Percentage Paid 5 Star reviews:38%

Percentage Non-Paid 5 Star reviews: 55%


## Summary

As we mention in the purpose of this study, our customers are interested to know if this Paid Reviews program would be beneficial for their business. Prior to provide our general conclusion, let's review the interpretation of each result described before:

1. The amount of Vine results is considerably lower than the amount of the Non-Paid review. The paid reviews represent only the 0.45% of the non-paid reviews.
2. The amount of 5 star reviews that the clients of this program are gettins is the 38% of the total paid reviews. In the other side, the manufacturers that are not customers of this program are getting more 5 star reviews for free (55% of the total reviews).

Besides that something to distinguish of this analysis is the behaivor of the reviews. When we look at the following tables we will see the breakdown of all the ratings for the paid and non-paid reviews are completely different, that could change a little bit the final rates when we combine both populations.

![Breakpoint summary1](https://user-images.githubusercontent.com/106939511/194192505-dfa80dbe-7277-4e9c-9b1e-3784de26703c.png)
![breakpoint summary2](https://user-images.githubusercontent.com/106939511/194192524-7ddab909-c09f-45a3-83e2-b8e79750786f.png)


**Vine reviews % per rating:**

1 star: 3.5%

2 star: 9.4%

3 star: 16 %

4 star: 33 %

5 star: 38 %


**Non-Vine reviews % per rating:**

1 star: 20 %

2 star: 5.4 %

3 star: 7 %

4 star: 13 %

5 star: 55 %


Our general conclusion based on these results is that we don't recommend the usage of this type of program in Amazon. It is a very small amount of the benefits at least for type of products. We would also recommend to perform the same analysis on more samples (more dataframes) just to confirm our hypothesis. 


