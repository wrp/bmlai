
Assignment 5.1

In this exercise, we analyze data/coupons.csv (from the UCI Machine
Learning repository) which contains data collected from a survey
on Amazon's Mechanical Turk.  The survey describes different driving
scenarios, including the destination, current time, weather, passenger,
etc., and then asks people whether they will accept the coupon if they
are the driver. Answers given that the users will drive there “right
away” or “later before the coupon expires” are labeled as “Y =
1”, and answers “no, I do not want the coupon” are labeled as
“Y = 0”. There are five different types of coupons—less expensive
restaurants (under $20), coffee houses, carry out and take away, bars,
and more expensive restaurants ($20–$50).

The notebook used to analyze this data is in
[bmlai_5_1.ipnyb](https://github.com/wrp/bmlai/blob/main/5.1/bmlai_5_1.ipynb)


To summarize the results:
'Carry out & Take away' coupons are the most likely to be accepted,
while `Bar` coupons are least likely.  Coupons at cheap restaurants are
likely to be used, as are coupons which will expire in the next day.
When the weather is sunny, coupons are more likely to be used, and drivers
that have a friend as a passenger are more likely to use their coupons.
