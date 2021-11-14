---
layout: post
title: "What makes automotive DevOps so hard?"
date: 2021-01-08 12:00:00 +0300
categories: 
  - automotive
  - agile
  - devops

comments: true
featured_image: /images/bonaparte.jpg
---


# DevOps and agile


# What's so special about automotive software?

Automotive computer systems might very well be one of the most complex in all industries. Real time criticality and functional safety are not easy things to achieve, and in automotive you need to consider those aspects for 50 to 100+ electronic control units (ECUs). As a result, a modern car might run with over 100 million lines of code, five times the amount of a fighter jet in comparison. 

At the same time, code reuse between generations is minimal due to highly optimized ECU specific code. Reuse is complex even between same-generation variants, since the market requires loads of tailoring, especially between regions. 

The automotive industry has modularized over the years. Original equipment manufacturers (OEM) — the companies that we identify as auto makers — mainly integrate the parts that tiers of suppliers produce. Contemporary software systems, however, require communication between all these systems, forcing an OEM to take responsibility also of software integration. This creates a problem: not many OEMs have the required software expertise yet. 

As a result, experts having knowledge about both manufacturing and embedded IT systems are highly sought after and often need to split their time between multiple projects.

# What challenges you face with DevOps in automotive?

OEMs claiming back software expertise is a positive trend, and I expect it to result in a better overall system design in the future. 

## The surprising drawback of standardization

Because of the complexity of automotive software, different standards have emerged that OEMs expect their software suppliers to follow. 

While standards are a good thing from the consumer point of view, they are also major sources of misunderstanding. For example, agile and ASPICE (Automotive Software Performance Improvement and Capability dEtermination) are compatible with each other, but the way ASPICE is presented creates confusion. Consider this V-model that is often referred to in automotive:

{% include captionimage.html src="v-model.png" caption="V-model describes the relationship between requirements and verification." %}

I's an easy mistake to understand it as stage gates, or to apply iterations only for the bottom part. In truth, ASPICE operates on the WHAT-level of development, and agile on the HOW-level, making them compatible. So in other words, you can define, document, implement and test anything that ASPICE requires within your existing agile processes, and not in a strict sequence. 

DevOps, however, is a different matter: automation level required to combine ASPICE with continuous delivery can be costly business with automotive. 

## The problems of embedded software

Tesla-pioneered over-the-air updates are a crucial enabler for DevOps-style development for cars: getting software updates in to a car without needing to physically stick a USB-device into it does all the difference. And just so, for example [Ford](https://corporate.ford.com/articles/products/over-the-air-software-updates.html) and [Volkswagen](https://www.continental.com/en/press/press-releases/volkswagen-id3-236882) have big plans for OTA updates. 

This change in style requires tremendous architectural rework from the auto makers. Current models are too rigid for imagining car as something other than a complete package that will not be changed later on. To allow delivering new features to existing cars, vehicle architectures need a full makeover. For example adaptive AUTOSAR is an attempt to provide something like that. 

Even with new architectural models, for DevOps the problem of automated testing remains. 


# How does the future of automotive DevOps look like? 

## Taking back the software development

## New architectures driven by electrification


# What can I do to help?

* Systems thinking
* Feature over component
* What about the standards? 