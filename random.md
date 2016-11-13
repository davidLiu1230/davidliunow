---
layout: page
title: random
permalink: /random/
---

This page currently hosts the noise complaint data project that I'm working on right now.<br />
As a sound-sensitive person I feel like I'm being ignored by the major house-hunting websites like craiglist/zillow/yelp. None of those sites provides much information on the noise level of the apartments. For the convenience of myself and those who also suffer from the "big city noise" problem, I will try to come up with a functional MVP that allows people to at least:<br />
1. View noise information/reviews by street address/apartment<br />
2. File a noise complaint to a street address/apartment<br />
3. TODO: View the data analysis on cities/neighborhoods(This will be San Francisco at the moment)<br />
4. TODO: Link the street address/apartment to yelp<br />

noise level: a slide bar, [unnoticeable, minor, unbearable, etc.]
noise pattern: the whole time, a couple times, sporadic, etc.
noise frequency: 3 pickers, first picker picks the frequency(‘every’, ‘every other’, ‘every once in a while’), second picker picks the day (‘day’,’weekday,’weekend’, Mon, Tues, Wed, etc.)
noise usually happen around: from-time to to-time, the accuracy should be hours.


Competitors: There’s one app called ‘The Noise’ on iPhone 
From the sales point, what differs this web app from the iPhone app ‘The Noise’?

pinpoints:
1.local investigator or housing regulators are slow on solving complaints
2.local investigator usually don’t care about complaints on minor noises or infrequent noises
3.sound sensitive people can be annoyed by even a tiny bit of noise, and different people have different noise tolerances
4.when people are looking for a new house/apartment for purchase/rent, they need to know the noise level of exactly that location. this is impossible to get besides driving there personally. And The Noise app doesn’t make the complaints public

The goal of this app: To help sound-sensitive people better choose where to live/where to avoid by providing a public platform to check the noise level with the accuracy on the neighbors.

Future plans of this app:
1. be able to update the status since the noisy people can move out, or the noise can stop for various reasons
2. be able to ping the person who posted the noise report of his/her place and ask them about more details (potential spam risk!!)
3. how to verify the authenticity of each complaint if it’s completely anonymous? Should we confirm the publish of the complaint by sending them a confirmation email? How does that work? Is that free?
4. 


{% include noise_complaint.html %}
