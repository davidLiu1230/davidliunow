---
layout: post
title: The Problem with Smart Pricing
date:   2017-05-02 20:33:16
categories:
---

Smart pricing describes any kind of real-time pricing algorithms that is done by a cluster of machines. A good example is how Uber or Lyft determines the 'market price' and 'surge rate'. I've always been on the corporate side of this idea. It maximizes the profit or/and revenue; it saves labor and directly/indirectly reveals the layered hidden cost; it also performs better than human under many conditions. I've seen it expanded to industries like car insurance, equipment rental, vacation business and many others that have long been using a fixed price strategy(a.k.a not real-time).

This is great. It's a powerful tool to leverage. In fact, many startups rely on this to bring in more cash so that they can get rid of rounds after rounds of investors. However, I think we should be cautious on designing the algorithms. Imagine a car sharing company that does the following:
```
Given a ford fusion owned by Tim

During the previous month, this car did 30 rentals
10 people rented for an average of 10 hours
20 people rented for an average of 1 hour

The current price is $8 per hour
This gives us a total income of $960

Based on the past data, the algorithm thinks that those 10 people with long rentals are static demands, whereas these 20 short rentals are more dynamic

The algorithm decided to raise the price to $9.5 for the current month

Now we just need 10 long rentals + 5 short rentals to match the previous income

At the end of the month, 10 long rentals and 10 short rentals were purchased, and it yields a total of $1045 income for Tim. Yay!
```
The owner of the car must be very happy with the result. What about those 15 renters? You could say that $1.5 is not a big deal, or that the market will oscillate around an equilibrium price as long as there are multiple competitors.  However, it doesn't alter the fact that right at this moment, 50% of the users got marginalized(and sad). Not to mention that many types of activities simply don't oscillate with the market. I feel bad for those that got "averaged out". This can become a more serious problem if we switch scenes to health insurance, housing market, college education, and so on.

At the end, smart pricing is awesome. In many cases, it brings down the cost and provides services to a broader audience. And I think it should be adopted by more industries, as long as it's carefully designed.