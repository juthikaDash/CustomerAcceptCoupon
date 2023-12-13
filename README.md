# CustomerAcceptCoupon

Will a Customer Accept the Coupon?
Context
-----------

Imagine driving through town and a coupon is delivered to your cell phone for a restaraunt near where you are driving. Would you accept that coupon and take a short detour to the restaraunt? Would you accept the coupon but use it on a sunbsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaraunt? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

Overview
----------

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

Data
----------
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

Deliverables
---------

Your final product should be a brief report that highlights the differences between customers who did and did not accept the coupons. To explore the data you will utilize your knowledge of plotting, statistical summaries, and visualization using Python. You will publish your findings in a public facing github repository as your first portfolio piece.

Data Description
----------
Keep in mind that these values mentioned below are average values.

The attributes of this data set include:

User attributes
----------------

Gender: male, female
Age: below 21, 21 to 25, 26 to 30, etc.
Marital Status: single, married partner, unmarried partner, or widowed
Number of children: 0, 1, or more than 1
Education: high school, bachelors degree, associates degree, or graduate degree
Occupation: architecture & engineering, business & financial, etc.
Annual income: less than $12500, $12500 - $24999, $25000 - $37499, etc.
Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she eats at a restaurant with average expense less than $20 per person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
Contextual attributes

Driving destination: home, work, or no urgent destination
Location of user, coupon and destination: we provide a map to show the geographical location of the user, destination, and the venue, and we mark the distance between each two places with time of driving. The user can see whether the venue is in the same direction as the destination.
Weather: sunny, rainy, or snowy
Temperature: 30F, 55F, or 80F
Time: 10AM, 2PM, or 6PM
Passenger: alone, partner, kid(s), or friend(s)
Coupon attributes

time before it expires: 2 hours or one day

Conclusion
-----------
1 - Based on these observations, what do you hypothesize about drivers who accepted the bar coupons?
2 - rivers who are over 25 years old have much more acceptance rate than drivers who are working driver goes to bar more than once a month.
3 - more than 25 years age group's going rate to bar is more than who goes to more than once and over age 25.
4 - Acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry is 100%
5 - go to bars more than once a month, had passengers that were not a kid, and were not widowed OR, go to bars more than once a month and are under the age of 30 OR, go to cheap restaurants more than 4 times a month and income is less than 50K , All the 3 conditions have same acceptance rate.
6 - So no significance in acceptance rate between drivers going to bar more than or less than once a month having kids as passanger at the time of receiving (accepting) the coupon.
7 - Drivers who drive alone seems gets more coupon and also accepts more coupon compraed to driver with friends, with kids and with partners
8 - Wondows uses least coupons
9 - Single and mariied both accepts more coupons
10- Students and unemployed accepts more coupons compared other groups.
11- Cheaper resturant, carryout & take away coupons and Coffee house coupon's acceptance rate is better compared to var and expensive coupon