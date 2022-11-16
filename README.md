# Amazon_Vine_Analysis

## Overview 

This analysis helps to determine if there is any bias toward favorable reviews from Amazon Vine members. These members are given products at no charge, from manufacturers and publishers who pay a fee to Amazon for this service, and then give reviews of said products. The analyzed dataset is coming from the Amazon category “Pet Products.”

##Results

![reviews](https://user-images.githubusercontent.com/105808695/202252348-0765f30a-7849-40d0-b090-d220d297053f.png)

#### Total Reviews

-	Paid Vine: 170
-	Unpaid: 37790

#### Number of 5-Star Reviews

-	Paid Vine: 65
-	Unpaid: 20605

#### Percentage of 5-Star Reviews

-	Paid Vine: 38.2%
-	Unpaid: 54.5%

## Summary

Out of 170 the vine-program reviews of Pet Products, only 38% returned a 5-star rating. This appears to be an unbiased, genuine result, especially when compared to the 54.5% of 5-star ratings from 37790 unpaid reviews. I would expect a biased result to be in the top 75% of the total ratings.

However, the numbers calculated in this analysis are only based on products which had 20 or more votes on the rating, with the “helpful” votes greater than or equal to 50% of the total votes. To provide more insight into the possibility of bias, we could filter the dataset to include all of the reviews which received at least 1 vote, as some vine reviews given could have been voted “unhelpful” and therefore may not have been included in the first round of analysis.
