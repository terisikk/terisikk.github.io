---
layout: post
title: "10 heuristics for an agile way of working"
date: 2021-12-12 12:00:00 +0300
categories: 
  - devops
  - agile
  - psychology

comments: true
featured_image: /images/devops/pi.jpg
---

I'm continuing with the trend of comparing psychological topics to agile. The latest book I devoured was *Risk Savvy: How to Make Good Decisions* by a risk scientist and psychologist Gerd Gigerenzer. I'll try to apply his ideas about heuristics into my daily work and offer some rules of thumb that I have found useful for effective software delivery and teamwork.

Dr. Gigerenzer offers handy advice on how to battle uncertainty in our everyday life, and bashes complex algorithms and models that fail to address highly volatile and uncertain topics. Gigerenzer claims that in the world of data, we have forgotten rules of thumb - heuristics - as a way to have simple answers to uncertainty. 

<!-- excerpt-end -->

The main idea to be taken from his book is this:
* If the problem domain is highly uncertain, there are multiple options and there is little data -> keep things simple.
* If there isn't much uncertainty, there are few options and you have plenty of data -> keep things complicated.

Keeping this in mind, here's a list of simple rules of thumb I have found to work better than complex models or calculations that try to address the same things. Simpler is better.

### *Don't create a team bigger than two pizzas can feed.*

I'm sure many of you have heard about this rule used at Amazon. There's loads of science and psychology behind optimal size for a team, but this is a simple and memorable rule to notice when your team has grown too large for effective collaboration, and needs to be split.

### *In Scrum, refine your backlog only for the next two sprints.*

I've seen a few times teams making the error of refining every single backlog item, overpopulating JIRA for the next quarter or even a year, only to end up deleting 80% of them later on. Don't fall into this trap. You can sink a lot of effort into dependency graphs and velocity analysis, but anything after the next two sprints is likely to change radically, leading to time-wasting re-refinement.

### *Estimates are uncertain. Don't over-analyze them.*

I've heard about RFQ:s where the contract lists a fine on every failed sprint or even falsely estimated story. I've seen seniority models where one criteria was "accuracy of estimates". Please, remember that estimates are "best professional guesses" and always uncertain. Do not hang yourself into them by trying to do complex analysis on hit-and-miss ratio for estimates. Focus on the value provided for customers, not the accuracy of your planning. 

### *Split work items to smallest deliverable, but not smaller.*

Split by interface. Split by operating system. Split by user segment. In what ever way you split your user stories, don't split them any smaller than you can deliver into production. Study spikes are fine, but no splitting stories into "implement, test and deploy". There's a huge risk of leaving a feature untested or not deployed. 

### *Limit work in progress to 'team size - 1'.* 

Multitasking is always bad, but a single-piece flow is not feasible always either. A good compromise is limiting the team's work in progress to a slightly less than the team size. This fosters collaboration, learning and knowledge transfer, since at least one person is always helping others instead of everyone working alone. 

### *A piece of software should do one thing and do it well.*

Forget cyclomatic complexity, number of lines etc. A good way to grasp whether a function, class or module is too large is to think whether it does more than one thing. If it does, split it up. 

### *Have zero failing tests and warnings.*

What percent of failures is acceptable for a delivery? The answer is **0**. Not 20%. Not "no new warnings". Not "I approve this failure, we need to deliver!". 

Really, get your development flow to a state where the only acceptable answer is 0 test failures. Either fix your tests and warnings, or remove them altogether if they are not important enough to keep healthy. And automate the analysis. 

### *Revert a change after 10 minutes of broken mainline.*

If you introduce a mainline-breaking bug that you cannot fix in ten minutes, even after storming the problem with others, it's time to revert it. Mean time to recovery etc. are cool metrics, but if your team is not that far into your DevOps journey, the ten minute rule is a solid one to keep the mainline clean. 

### *Trunk based development over complex releasing models.*

I get it, in some industries never patching older releases might not be possible. However, whenever you can skip that, do it. It's a million times simpler to only fix forward and do releases from your version control mainline than trying to maintain several older releases. It means less time wasted on developers fixing bugs to multiple release branches, "maturing" those branches and having a complex release calendar. 

### *First in, first out for service desk work.*

Prioritizing by affected user count, item age, criticality, weighing in different SLA:s... When you have a fluid service desk team, you will be able to pick up new tickets solely based on the order they arrive in, apart from critical outages that usually require wider intervention anyway. If you don't, you will end up multi-tasking and re-prioritizing all the time. 

### *BONUS: a complex model for service desk work analysis*

As a bonus, here's one situation where I have found a little more complex mathematical model to be useful over a more simple alternative: control charts for analyzing service desk work. 

A usual model that I have seen for having a Key Performance Indicator for service desk efficiency is average time to resolution. However, averages tend to hide problems a lot. You could have a decent average time to resolved, but it could be the result of jumping immediately to every new task, solving the easy ones very quickly, and ignoring hard cases. 

This is why I prefer control charts that show both the average and *variance*. With control charts, you can more easily focus on providing *predictable* service desk delivery. Predictable is often better than fast, since you can set realistic expectations to the customer about the resolution time instead of providing obscure averages. 

---

*Did you like my rules of thumb? Do you have your own that you would like to share? Leave a comment below or to LinkedIn.*

*I’m an agile/devops fellow who likes to understand what makes people tick and why we act like we do.*