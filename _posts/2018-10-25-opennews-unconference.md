---
layout: post
title: OpenNews Unconference on Journalism Tech 2018
date: 2018-10-25 07:00
tags: [conference, journalism, digital, technology]
permalink: /opennews-unconference-2018/
---

I facilitated a discussion session called "Doing things more than once" &mdash; on the challenges in making things designed to be re-used (versus producing one-off projects). The discussion covered templating, productionising, code refactoring, maintenance debt, documentation, training, and institutionalising knowledge.

![](/images/opennews/intro.JPG)

## What makes it hard

- Resources. Building things designed to be robust enough for re-use generally takes longer than building something for one-off use.

- Time needed for refactoring. This is often not recognised by stakeholders and therefore not budgeted for.

- Lack of standardisation. Different teams/people use different tools, frameworks, or data models making it hard to make things that can be reused. This is also a trade-off, sometimes you _don't_ want to be locked in by standardisation, given the average lifecycles of code frameworks.

- Training. Building something that can be reused often means training others how to use it, which requires time and resources.

- Story vs product. Most newsrooms think of what they produce as stories (i.e. short half-life, publish and discard) rather than products (i.e. longer shelf-life, publish and maintain)

- Sometimes even when the recurring event looks similar on the surface (Elections, for example), the underlying story is different every time. Sometimes the data input differs as well

![](/images/opennews/hard.JPG)

## What helps

- data-informed decision-making on when you try to make something reuseable (and when it's not worth it)

- Modularisation. This could be for the CSS. Or it could be separating the content from the codebase. This is easier if you have a good data model and a good underlying information architecture that lends itself to modularisation

- Resource constraint actually sometimes helps. In the early days of FullFact, there were so few people that everything had to be re-usable and doing one-off projects were seen as a luxury.

- Being really clear about what you are building. Are you building for one-off, or are you building for re-use?

- Recognising that there is an inevitable central tension between making an editorial product vs making a technology product, and that one will take priority over the other. This is often hard because it goes right to the identity of the company (do they think of themselves as a tech company? or a publisher?) 

- Good communication and common understanding. Being really honest and telling people how long it will take to build something reuseable / to refactor code / to build a generalised tool helps to set the right expectations

- Documentation

- Integrate UX people. Product people tend to be good at communicating upwards. UX people can help communicate sideways (to other journalists/users)

- Find a better 'product discovery pathway'. i.e. a better way to hand off projects from the project team that built the one-off story, to the product team that could make it reuseable and take on the work of supporting and maintaining it.

- Have your project and product teams use the same code frameworks (i.e. React). This makes the hand-off easier.

- Have a system / architecture that supports archiving.

![](/images/opennews/helps.JPG)


