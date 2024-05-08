## Professional Certification in AI/ML
### Practical Application Assignment 5.1
### [Project Link](https://github.com/Raesu/pcmlai/tree/master/Module%205/assignment_5_1_starter)

### Objective
The objective of this assignment was to analyze a set coupon acceptance data and find trends in acceptance rate across different characteristics.

### Findings Summary
- The data was already of high quality. I dropped one column due to excessive NAs. Some columns that you'd expect to be numeric are actually a mixture of numeric and labels like '50plus'. Since there weren't many values overall, I continue to work with them as-is.
- Overall coupon acceptance rate was quite high (57%). From personal experience I am not likely to accept coupons that are given to me ad hoc, so interesting to see I am not a majority.

#### Bar Coupons
- Coupon acceptance was highest among people in their 20s and 30s, who did not have children, and were habitual bar goers.
- Lower income individuals were less likely to accept bar coupons.

#### Take Out Coupons
- Temperate has a small impact on acceptance - as expected, cold temperature is correlated with greater coupon acceptance.
- When looking at destination of the drivers, people driving home already were the most likely to accept a coupon. People going to work were the least likely. This makes sense as people going to work likely shouldn't show up with take out, and they probably have food at work already.