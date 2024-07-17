# assigment5_1
Berkeley Emeritus AI/ML course assignment

## Customer Coupon Data Analysis Report

### Description

This project was an analysis of coupon data to determine whether or not customers are
likely to accept a coupon for a nearby business location. The analysis involved exploring
the data in several different ways to gain insights.

#### Step 1 - Data Review and Cleaning

After first reviewing the data, I noticed several things. First, the "car" column did not
contain a useful set of values for analysis, so it was dropped. Next, the dataframe was
examined and the fields with null values were identified. Finally, the 'passanger' column
was corrected to 'passenger'.

#### Step 2 - Methods and Analysis

This analysis was performed by loading the provided coupons.csv file into a pandas
dataframe and then producting a comparative analysis of various subsets. Plots were
used to help visualize the data.

#### Conclusions

1. More coupons for coffee houses were accepted than for any other type. Coupons for
   restaurants in the $20-$50 range were the least likely type to be accepted.
2. Fewer coupons overall were accepted in colder temperatures than in warmer ones.
3. People who went to bars more than 3 times a month were twice as likely to accept
   a bar coupon
4. People who go to bars more than once a month and are over 25 are nearly 3 times
   as likely to accept a Bar coupon compared to other demographics
5. People who go to bars more than once and month and had passengers that were not
   a kid and had occupations other than farming, fishing, or forestry are twice
   as likely to accept a bar coupon
6. A higher percentage of Males are likely to accept a bar coupon
7. People without children are more than twice as likely to accept a bar coupons as those without
8. Single people are the most likely to accept a bar coupon. Widowed and divorced people
   are the least likely.
9. People are more likely to accept a coupon if their destination is 'No Urgent Place'
   rather than Home or Work
