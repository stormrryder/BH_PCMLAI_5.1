# BH_PCMLAI_5.1

## Assignment 5.1 for Berkeley Haas - Professional Certificate in Machine Learning and Artificial Intelligence

### Notebook
https://github.com/stormrryder/BH_PCMLAI_5.1/blob/main/coupns.ipynb

### Findings
The initial data analysis revealed the following:
1. There is a data collection issue regarding the type of car driven. This information is mostly missing and could not be used in this analysis.
2. 57% of the coupons are accepted while 43% are rejected
3. More coupons for Coffee House have been offered than any other types
4. Coupons for carry out and cheaper restaurants have highest positive acceptance
5. Coupons for bar and more expensive restaurants have negative acceptance
6. Temperature values are discrete and limited to 30F, 55F, and 80F
7. Most coupons were offered when temperature was 80F
8. As the temperature increases, coupon acceptance increases
9. 59% of bar coupons are accepted while 41% are rejected
10. Bar coupon acceptance increases with bar attendance
11. There is not a significant different in bar coupon acceptance between those less than 25 vs those over 25
12. Having adult passenger has a slight positive effect on bar coupon acceptance of about 2%.
13. Low income earners that frequently go to cheap restaurants are less likely (about half) to accept a bar coupon. Possibly indicating that low income earners have to chose to spend on restaurant or bar, but cannot do both. This would have to be investigated separately.
14. Cheaper restaurant coupons are positively accepted regardless of passengers. And are even more likely to be accepted when with partner, kids or friends than alone.
15. Coffee House coupons are positively accepted when driving with a partner or friends but negatively when with kids or alone.
16. Bar coupons are only positively accepted when driving with friends.
17. Carry out coupons are positively accepted (roughly 3:1) regardless of passengers.
18. Expensive restaurant coupons are only posively accepted when with driving with a partner.

### Recommendations
1. Data collection issue regarding car type should be investigated
2. A coupon acceptance threshold should be identified. The threshold would identify the profitability of the coupon. Coupon types with acceptance below the threshold should be evaluated for improvements or elimination.
3. If multiple coupons are presented to a driver, the coupons should not compete against each other. In case of conflict, an algorithm should be implemented to present the coupon type that is most likely to be accepted.
4. As there is some correlatio between coupon acceptance and passengers, the coupon app should be upgraded to use nearby devices to determine the type of passengers.

### Next steps
1. Investigate whether coupon expiration creates a sense of emergency that increases coupon acceptance.
2. Continue data analysis to define 3 personas for each coupon types that are most likely to accept the offer.