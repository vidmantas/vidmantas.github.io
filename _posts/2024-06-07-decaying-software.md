---
layout: post
title:  "Decaying Software"
tags: [ communication, accountability, ]
featured_image_thumbnail: assets/images/posts/2024/decaying-software_thumbnail.jpg 
featured_image: assets/images/posts/2024/decaying-software.jpg
---
Software is not a physical object, so the concept of decomposition is quite unnatural to consider in such a context. However, this doesn't mean there's no decay over time. 

<!--more-->

### How It Happens

Every engineer faces software decay once they try to work on a project that has been abandoned for longer than a year. In some cases, it's just about getting the proper updates in, but more seriously, forgotten systems are sometimes easier just to bury and write anew.

Generally, the amount of "rot" gets more prominent because of two main reasons: 
* Getting outdated technically, or
* Getting behind business-wise

Both happen naturally over time unless the organization is committed to paying at least some essential upkeep cost. However, both are equally dangerous in backfiring in the most unusual ways.

### Organizational Debt

Getting behind business-wise is not only about missing this new department org that launched 2 years ago or missing convenience features and UX optimizations. It's an increasing risk of failing to comply with various laws and regulations, potentially opening the doors for serious investigations nobody ever needs. GDPR and OFAC sanctions - to name a few, ignored for long enough, will give any business a lot of headaches. Especially if abandoned software is available publicly. 

The biggest mistake here is the dangerous assumption that a snapshot of a valid state five years ago is as good as today.

### Iceberg Technical Debt

Interestingly, the technical debt on such abandonware is usually considered more straightforward to fix if you need to revive the project. Sometimes, this is the case, but the highest risk appears with the iceberg effect and exposure to potential security attacks while all holes have been patched up.

The iceberg effect happens when the dependencies you need to upgrade are no longer backward-compatible, their API has completely changed, or they may not even be maintained anymore. The community might have just moved on to some better solution, so instead of a version bump, you get to rewrite parts with a completely new library.

Exposure to severe security holes is relatively self-explanatory. To add, nobody monitors abandonware as well, so you might not even be aware of the "stuff has been going on," a technical issue is becoming a pretty severe legal accountability problem, especially if personal data was involved.

### Avoidance

There's only one way to avoid such headache-inducing abandonware: be absolutely brutal with your software. It has to be either adequately maintained or mercilessly taken down—it's as simple as that. 

But the challenge is that in today's organizations of growth and revenue, nobody is getting a medal (or bonuses) for shutting down unnecessary systems. So, it _must_ be codified into the product management lifecycle right from the beginning, and the accountable owner must be appointed from the inception of any piece of software the company runs. Leaving it to a "later stage to think about" is the highway to all the abovementioned problems.

If your organization is already facing these issues, make sure your communication about them is right to the ear of business owners, as it's not a technical problem but an organizational one with very real consequences for the company.

### Physical World Analogy

Running your own software is similar to owning a car. If you just park it for years, gasoline will break up, brakes will rust, the battery will die, and all kinds of other pleasantries will make the car unusable without more or less serious upkeep investment before it can be driven again.

<small>
  Photo by gina [christoforou](https://www.pexels.com/photo/brown-utility-truck-on-grass-1051276/)
</small>