---
layout: post
title: "Sustainable DevOps: Environmental Responsibility"
date: 2022-02-14 10:00:00 +0300
categories: 
  - agile
  - devops 
  - philosophy 

comments: true
featured_image: /images/bruce-lee.jpg


---


- Shein
- Siilimetsä
- Sustainability
- AWS Co2
- Pipelines and CPU capacity
- https://cloud.google.com/carbon-footprint
- power generation


I often think about that do I make my peers, customers or the world better or worse with the work I do. When I see labels like DevOps or Agile used for things that actively harm people or the planet, I tend to get very anxious. This blogpost is a part of a series of attempts to make you think about sustainability and responsibility alongside your DevOps transformation, so that you will hopefully use your newly found powers of teamwork and automation to make a positive impact on the society around you. 

This time I will focus on environmental responsibility of your DevOps way of working. 


## Impact of pipelines

Scaling up your automation and CI/CD will at least initially make you consume more computing capacity than before, there's no doubt about it. In the previous company I worked for, one of the top concerns was always how to get more computing capacity for the on-premise CI/CD-system and keep up with increase in demand for that, when teams transitioned from running their builds only weekly or nightly to multiple times per day. It is clear that this was not an environmentally sustainable model for scaling. There were obvious spikes in resource demand based on the time of day, and the rest of the time the computing capacity was idling. 

There have been some studies that indicate that this anecdote is true for others too. Research from Accenture states that IaaS migration can reduce your infrastructure carbon footprint by 84%, or even as much as 98% if you adopt cloud native approaches[^1]. So if you want to be greener, a cloud platform adoption is a necessity when scaling out the automation required by DevOps practices. 

## Cloud adoption and energy efficiency



## Constant experimentation in ultra-fast fashion

Out of context, Shein does a lot of the things that DevOps, Lean and Agile promote. Their business model is software driven and they make constant experiments and A/B testing based on data to react to customer need in lightning speed. They use heavy automation to make just-in-time orders and minimize the inventory of merchandize. So what's the problem?

The missing ingredients are sustainability and responsibility. What I want to promote when talking about agile topics is how they can help to make the life of your customers and your employees better, not only how to make your shareholders more money. And I think that includes the responsibility towards the environment we live in and even the people that are *not* buying your products or using your service. 

And Shein is not shining on that front: despite pretty words, they fail to disclose any details about their carbon footprint and their whole mission seems to be to dump out new cheap plastic items day to day. No matter how lean your value stream and production is, if your produce tons of low-quality products that by design your customers throw away very quickly, you are actively making things worse. 

## What to do?

As always, I will refer to the same principles that I use in my work for fixing complex issues like this. The "Plan-Do-Check-Act" cycle for starting to fix something so intangible as social responsibility starts with recognizing the opportunity for a change towards something better. Now that you've read this post, you have hopefully already recognized the problem to work. 

Next thing to do would be to look at the data that you have at hand. For example: if you are using AWS, check out your carbon impact from your billing page, and then take a look on the Sustainability pillar of AWS Well-Architected about ideas how to reduce it. 

Keep your action small, something you can implement and test right away. 

After formulating a quick plan on how to get better, it's time to act. 




## References

[^1]: [Accenture - The Green Beind The Cloud](https://www.accenture.com/_acnmedia/PDF-135/Accenture-Strategy-Green-Behind-Cloud-POV.pdf)
[^2]: [The Guardian: _How Shein beat Amazon at its own game and reinvented fast fashion_](https://www.theguardian.com/fashion/2021/dec/21/how-shein-beat-amazon-at-its-own-game-and-reinvented-fast-fashion)
[^3]: [AWS Well-Architected - Sustainability](https://docs.aws.amazon.com/wellarchitected/latest/framework/sustainability.html)



