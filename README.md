# Exploratory Data Analysis

This repository contains my Exploratory Data Analysis using python Pandas, matplotlib and searborn for visualizations. This analyses the factors influencing acceptance of coupons by drivers en route to a destination.

## Overview
This dataset, obtained from the UCI Machine Learning Repository, comprises approximately 12k records, collected via a survey conducted on Amazon Mechanical Turk. The survey outlines various driving scenarios, including details such as destination, age, income, weather conditions, passengers, and records respondents' decisions on whether they would accept a coupon while acting as the driver.

**Link to Jupyter Notebook:**


## Key Insights:

1. ### Overall Acceptance Rate
   * Total Proportion of Accepted coupons contributes to ~58% across categories and scenarios
2. ### Impact Of Destination
   * The likelyhood of people accepting the coupon is more (~65% Acceptance rate) when they have no urgent work. While, there is only 50% probability, that people will consider accepting the coupon, when they are heading to work/home.
3. ### Hypothesis on Bar Coupons Acceptance Rate
    * Only 40% of the bar coupons issued are accepted, while the acceptance rates for other coupons are higher than their respective rejection rates.
    * Impact Of Habit
        * People who visit bars more than three times a month are defined as Frequent visitors. They have a higher likelihood of accepting coupons. The likelihood of frequent visitors to accept is 77%, while it decreases to 50% in case of less frequent visitors.
    * Impact of Age
      * People under the age of 25 are less likely to accept bar coupons.
    * Impact of Income
      * Individuals with an annual income of less than $50k are more likely to reject bar coupons.
4. ### Impact of Passengers on Coupon Acceptance
    * 50% of coupons are accepted when traveling alone without co-passengers.
    * Only 7% of coupons are accepted when traveling with kids.
5. ### Analyzing Acceptance Rate Across Categories
    * For all coupon categories, the rejection rate exceeds the acceptance rate.
    * The only exceptions are the coupons for cheaper restaurants (Restaurant<20) and Carry Out & Take Away coupons. These have higher acceptance rates than rejection rates. This shows that Food Coupons are preferred widely.
6. ### Analysing Food Coupons Based on Various Considerations
   * Impact Of Driving Direction
      * The acceptance rates of (Restaurant<20) and Carry Out & Take Away coupons are ~70% even when the assigned location is in the opposite direction of the destination.
        Even a detour doesn't impact the decision.
   * Impact of Passengers
      * Initially it was stated that only 7% of overall coupons are accepted when travelling with kids. But in case of Food Coupons, the rejection rate when travelling with kids is lower than the acceptance rate.
   * Impact of Habit
       * People who visit economical restaurants less than once in a month or never are considered 'Not Frequent Visitors'. In case of (Restaurant<20) and Carry Out & Take Away coupons, even the 'Not Frequent Visitors' acceptance rates are highers than the rejections.
   
      
    







