---
layout: post
title: "Theory of Constraints and League of Legends"
date: 2021-11-14 12:00:00 +0300
categories: 
  - business
  - lol
  - games

comments: true
featured_image: /images/lol/augmented.jpg
---

Ah yes, the Theory of Constraints (ToC) by Dr. Eliyahu Goldratt. A theory of prioritizing your improvement actions to the biggest bottleneck within your workflow, one of the best yet simplest theory of lean production management. Revised on factory floors and now utilized in many other places, like in the IT industry. 

And now I will make a tongue-in-cheek attempt to explain that theory with the help of... League of Legends? What could go wrong?

{% include captionimage.html src="lol/league.png" caption="League of Legends." %}

<!-- excerpt-end -->

[League of Legends](https://www.leagueoflegends.com/en-gb/) is a hugely popular competitive mutliplayer game where you battle in a big arena with your team against another, and it has inspired me to improve things in my worklife, and also the other way around. So let's get to it. 

## The Goal

In business context, your company hopefully has some higher purpose - a goal - than just generating money, like making people happy by serving good food. However, within the current capitalist system, the only way you can usually achieve your higher purpose is by making more money than you lose and investing that money to chase that goal.

In League of Legends, the ultimate goal for many players is increasing their rank to for example the status of "Challenger", the biggest skill tier you can reach in-game. Whether it's the sense of accomplishment or just wanting to boast to your friends how awesome player you are, there are millions of players who actively pursue this goal of climbing up the ladder. 

{% include captionimage.html src="lol/tiers.png" caption="The road to challenger." %}

So, how do you reach a higher rank in League? To simplify things a bit for the unaware: the only way you can reach a new tier is *winning more games than you lose*, and slowly climbing up in the rank ladder. Each win grants you a dash of League Points (LP), which in turn increases your comparative rank to others. Vice versa, losing a match costs you about the same amount of LP.

There's a whole lot that goes to this, but for the sake of this blog post, let's stick to this simplification and think of "LP gain" as the meter of your success, and explain Theory of Constraints through it. 

A word of warning, LP gain is just a secondary measure: you can gain a truckload of LP and *still be miserable*, unless you can get satisfaction from that achievement. The same is true with money vs purpose. So now you know.

## Conversion to business value

A work item (ticket, order, ...) is converted to value only after it reaches the customer or end user and they like the result, not a second earlier. Sure, you can get paid earlier, but unless you have truly created something valuable, you will either get a high number of returned products and unhappy customers, and lose money. 

So, in the process of climbing the LoL ladder, what is our "work item"? That's right, it's a match of League. A ~30 minute game that you must win in order to convert your efforts to the value of LP gain. 30 minutes of fighting, farming, flaming and forfeiting. 

Similarly to a work item not converting into value until it happily reaches the customer, your League match does not convert to LP until you actually manage to destroy the enemy Nexus before your enemy does the same to you. Getting the most kills or the highest amount of farm does not matter at all unless that Nexus goes down. In this context, you yourself are the biggest constraint. You, and no-one else, must ensure that you are able to win more games than you lose. 

{% include captionimage.html src="lol/lp.jpg" caption="Slowly gaining that sweet LP." %}

The stakes are high, since approximately 50% of time you will lose, unless you are able to get better over time and push those win rates up. And if you think those failure rates as high, consider that about the same applies for example to Software Development. According to [The CHAOS Report 2015](https://www.standishgroup.com/sample_research_files/CHAOSReport2015-Final.pdf), around 40% of Software Projects are not considered valuable or satisfactory by the customers. That's a lot of time and money wasted. Since you are the one reading, you are also now responsible for making things better within your company.

But, to keep things a bit more interesting, let's jump to the individual League match level and think about what goes into converting that match into LP. 

## Winning a match and the Five Focusing Steps

The theory of constraints dictates that there is usually a single critical limiting factor, the constraint, the keeps you achieving your goal, and systematically improving on that constraint will "break it". Similarly, there is probably a single biggest bottleneck at any moment that keeps a League player from climbing.

"The Five Focusing Steps" is a method to find and break that constraint. A bit of jargon (targon?) in the following cycle:

{% include captionimage.html src="lol/focusing-steps.webp" caption="To truly see the stars, I climbed." %}

Let's break that gem down and think what this would mean in our League of Legends metaphor.

## Identify the Constraint

To start working on the biggest problem, you must first identify it. So let's head into the Summoner's Rift. When you break down the goal of "Destroy the enemy Nexus", what sub-goals you need to achieve to do that? Do you need to kill the enemy team?

Well, surprisingly, killing enemy champions is not a biggest obstacle on your way to victory. From the process point of view, especially in the early game, enemy champions are merely a distraction that keeps you from reaching your sub-goals, and killing them is just an enabler. An important one, to be sure, but you need to keep the goal always in mind. 

What stands in your way to the enemy Nexus are the enemy minions and turrets. That's right, these fellas. 

{% include captionimage.html src="lol/towers_minions.png" caption="The real pieces of work." %}

You cannot advance to the enemy Nexus without destroying the turrets first. And what needs to happen that you can break them? You need to get strong enough to keep those pesky enemy distractions from preventing you. These hunks of stone are the work items that you must process in order to reach the end goal. And the minions are your biggest source of material, similar to raw materials in a factory.

An example of a constraint that might keep you from destroying these towers in a timely fashion: converting income to items. Remember what I said about converting work to value? Well, the same works on this level too: the gold that you earn from killing minions (or champions) is not converted into power unless you *actually spend it*. 

One way to identify a constraint is to see where you gather "inventory" that just sits there, waiting to be processed. In League context, your inventory would be unspent gold, or gold that the minions carry. All the time that gold sits in your pocket or within the raw material (minions), you are not getting value out of it. It means less items, less power and less opportunities. So, your constraint in this case would be converting gold to items.  

## Exploit the Constraint

Now that you have a hypothesis on what the constraint is in a match, it's time to exploit it. That means taking any quick wins that are possible to increase the "throughput" of the constraint. In this example, that would mean increasing your minions-to-gold or gold-to-items conversion rate.

The ToC identifies several ways to do this. First, ensure continuous operation. Always have someone taking on the incoming work (minions). Even if you are an efficient gold farmer, you should be offloading the work to someone less efficient when needed. For example a support could push or hold the wave for you when you take a trip to the shop. This is still more efficient than not keeping the conversion running and losing work items to your own turret.

Second, keep the quality of processed items high: only process parts that meet the quality standard. In League this could mean not chasing that useless Teemo to the jungle while you have valuable minions running down your lane, ready to be converted. They are worth much more. 

{% include captionimage.html src="lol/teemo.png" caption="Dont' fall for that global taunt." %}


## Synchronize to the Constraint

Now that you have taken the quick measures to increase the throughput of the constraint, it's time to synchronize the other parts of the process to it. In other words, to make sure that there isn't more work coming to you than you can process.

{% include captionimage.html src="lol/conversion.png" caption="Conversion in progress." %}

For example, you could take better base timings so that you can do the conversion during a break in "production" - that is, during the times that minion waves are crashing to the enemy turret and not yours. Otherwise you will not get any income from those. Especially when playing a gold-reliant role like an ADC, make sure to synchronize any other actions between the minion waves. 

The same goes for other power generating objectives. Make sure you synchronize your rotations so that you are not missing the next important objective, like a dragon. It's more important for the end goal than "processing" something less valuable. 

So, in within your business you would want to ensure that the constraint always has enough people working on it, and it is always given the highest priority in actions like maintenance or rotations. 

What was the LoL goal again? Ah yes, push the turrets and the Nexus. Whatever you do, remember to keep doing that.

## Elevate the performance

So you have done the quick actions and synchronized your work to honor the constraint. What now? How to make things better? 

Now is the time to take big investments. In a factory floor this would mean analyzing the biggest losses of productivity and fixing them one by one with enough effort. It's not that different with League. You need to first analyze your biggest weaknesses that keeps your item acquisition down, and this means that you need to start reviewing and analyzing your past games from this perspective. What where the biggest factors that made you lose income? Bad recalls? Bad farming? Dying too much? You find out.

{% include captionimage.html src="lol/yasuo.jpg" caption="I alone decide my fate." %}

This part will take time and resources, as opposed to the quick wins. Things might even slow down while you experiment with better options, but as long as you keep improving the constraint, you will break it. So keep improving slowly and steadily.

## Repeat the process

So, think you've done everything you can to break the constraint? Well did you? Evaluate. 

Find out if you are still limited by that factor, or something else. If after all these efforts your constraint still stays the same and your throughput is too limited, it's time to start from the beginning. Take a fresh look on your hypothesis and try to identify whether it was correct. Find out new actions. 

In League, there will be a ton of new things that will keep limiting you once you rise in the ranks, so continuous learning will be required from each game, otherwise you will always be limited by yourself alone. Not your team mates, not matchmaking, not Riot. You. 

And in business? No excuses, you need to do the same. Enable continuous learning within your company ***now***.

Rinse and repeat.

{% include captionimage.html src="lol/nasus.jpg" caption="The cycle of life and death continues." %}


---


*I'm an IT-consultant, Agile-freak and a low-elo League player that likes describing things with metaphors from games.*

*Did you like this kind of game metaphor? Was it more useful for business or as a League guide? Leave a comment to the blog or throw me a message in Linkedin. I have used League and video games as a metaphor for teamwork and IT industry before, and would like to keep doing that, since it's fun to combine two things that you like and learn from both in the process.*
