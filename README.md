# Amazon_Vine_Analysis

## Overview of the Analysis
We have been asked to analyze Amazon reviews written by members of the paid Amazon Vine program, which allows manufacturers and publishers to received reviews for theri products. I have chosen the video game product reviews to anaylze in PySpark and load the data into pgAdmin. Using this data, we can confirm any bias towards favorable reviews from Vine members.

## Results
- How many Vine reviews and non-Vine reviews were there?

![Alt text](https://github.com/JoshTrewhella/Amazon_Vine_Analysis/blob/main/Images/paid_vine_total.PNG)

- How many non-Vine reviews and non-Vine reviews were there?

![Alt text](https://github.com/JoshTrewhella/Amazon_Vine_Analysis/blob/main/Images/unpaid_vine_count.PNG)

- How many Vine reviews were 5 stars?

![Alt text](https://github.com/JoshTrewhella/Amazon_Vine_Analysis/blob/main/Images/total_vine_5star.PNG)

- How many non-Vine reviews were 5 stars?

![Alt text](https://github.com/JoshTrewhella/Amazon_Vine_Analysis/blob/main/Images/total_nonvine_5star.PNG)

- What percentage of Vine and and non vine reviews were 5 stars?

![Alt text](https://github.com/JoshTrewhella/Amazon_Vine_Analysis/blob/main/Images/percentages.PNG)

## Summary
Seeing that 51.0% of the paid reviews are 5-stars and 38.7% of the unpaid reviews were 5-star implies that there a bias and you are more likely to get a higher review if they are paid. 

For further analysis I would include all review ratings to see if average review is higher for paid than unpaid. 
