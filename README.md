# Couponacceptance
Data sciences project to predict driver coupon acceptance 

Context:

Envision cruising through town, and suddenly, a coupon pops up on your cell phone for a restaurant nearby. Would you divert for a quick detour to use the coupon immediately? Or would you pocket the coupon for a subsequent trip? Perhaps you might disregard the coupon entirely. Now, what if the coupon was for a bar instead of a restaurant? How about a cozy coffee house? Would you accept a bar coupon if you had a minor passenger in the car? What if it was just you and your partner? Does weather influence your likelihood of accepting the coupon? What about the time of day?

While proximity to the business is undoubtedly a factor in delivering the coupon, what determines whether a driver accepts the coupon once it's received? What factors influence a driver's likelihood of accepting a coupon?

Data:

The data, sourced from the UCI Machine Learning repository, was gathered through a survey on Amazon Mechanical Turk. The survey presents various driving scenarios, including destination, current time, weather, presence of a passenger, etc. Participants were then asked whether they would accept the coupon if they were the driver. Responses indicating an intention to drive 'right away' or 'before the coupon expires' are labeled as 'Y = 1', while responses indicating 'no, I do not want the coupon' are labeled as 'Y = 0'. The coupons are categorized into five types: less expensive restaurants (under $20), coffee houses, carry out & take away, bars, and more expensive restaurants ($20 - $50).

Findings:
Bar Coupon
The acceptance rate for bar coupons is notably high at around 70% within the customer cohort that frequents bars more than once a month, has no children as passengers, and is above the age of 25.
Restaurant(<20) coupon

ased on the above analysis the Restaurant(<20) coupon can be targeted to customers with features as below
- time of coupon 2PM lunch and 6pm Dinner 
- temerature is above 49 
- destination as not urgent
- Occupation in Student or Unemployed

This will improve Acceptance rate to 80 % from current 70%

Refer the below notebook for the data analyis for above findings
[here](https://github.com/krishnawin/Couponacceptance/blob/main/prompt.ipynb)
