---
layout: post
title: Notes from the Tapestry and NICAR conferences
date: 2016-03-19 12:00
tags: [digital, media, storytelling, data journalism]
---

I went to the [Tapestry](www.tapestryconference.com) and [NICAR](http://www.ire.org/conferences/nicar2016/) conferences in Denver earlier this month. Here are my notes. These are thoughts triggered by the sessions and not comprehensive summaries.

##Tapestry

####From [Scott Klein's](https://twitter.com/kleinmatic) talk

Literacy in data visualisation is by no means an unstoppable march of progress. Ever since newspapers [first published](https://www.propublica.org/nerds/item/infographics-in-the-time-of-cholera) graphics in its pages, each generation of visual journalist has had to re-educate the public on how to read and interpret their work. Literacy of certain graphical forms can and has been lost &mdash; during the American civil war newspaper often published complex battle maps without extensive explanations because they were prevalent. Today we would find them hard to comprehend. This leads to some important questions:

- What is the level of literacy we can expect of our readers? Given our publishing model of no longer just writing for a narrowly defined group of FT subscribers but also seeking out new audiences on social media, what becomes of our ability to educate and raise the level of our readers' literacy? 

- Can we rely on *any* lasting progress being made, or is each new generation forever doomed to repeat the same arguments and go through the same process of educating readers about data visualisation?

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Avant guard visualizations in 1849&#13;<a href="https://twitter.com/hashtag/Tapestryconf?src=hash">#Tapestryconf</a> <a href="https://t.co/oVBABawPEC">pic.twitter.com/oVBABawPEC</a></p>&mdash; Jenny Richards (@jnnyrchrds) <a href="https://twitter.com/jnnyrchrds/status/707605190153732100">March 9, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
<br>

####From [Jessica Hullman's](https://twitter.com/JessicaHullman) talk

We often want to display a sequence of graphics or charts to convey a point. There are a limited number of types of transitions from one to the next. Are certain types better or more preferable than others? Jessica's research shows that readers prefer transitions with lower cognitive cost than those with higher ones, i.e. transitions that are easier to grasp/understand.

Specifically, for transitioning between several maps, she found that changing multiple things in one transition imposes a high cognitive cost. When changing only one thing, the cognitive cost of time transitions < dimension/measure transitions < heirarchy transitions

**Time transition**:
Population density in 1900 ⟶ population density in 2000

**Dimension transition**:
Population density in London ⟶ crime rate in London

**Heirarchy transition**:
Population density in the UK ⟶ population density in London

She also noted that this model needs to be refined to consider the sequence as a whole. At that macro level, pattern recognition could reduce the overall cognitive load and that would not be taken into account if you looked only at cost of each individual transition. For example, while zooming in (i.e. heirarchical transition) has a high cognitive cost, it may actually be easy for the reader to understand what's going on when it is the third time they do a country-to-capital city zoom.

Further questions:

- Is cognitive cost the only measure to optimise for? Could there be two sequences that convey the same amount of information, but where the one that requires a higher cognitive cost to comprehend is actually preferable? For example because it gives the reader something else besides information (such as an emotional impact) and/or because it has some other mechanism that compels the reader to persist despite a higher cognitive cost? 

- Even if we are optimising for lower cognitive cost, what is the right trade-off between the amount of information conveyed and the cost needed to comprehend it? I think the answer is that in most cases, the information is encoded in the visualisations themselves and transitions are mere friction, and therefore the cognitive cost of transitions ought, as a rule of thumb, be minimised.

- What other methods or techniques help lower congitive cost? We know well-written annotations and titles help lower the cognitive cost of understanding a (single, static) data visualistion. What helps lower the cost of comprehending transitions? Animating the change?  

####From [Nick Sousanis's](https://twitter.com/Nsousanis) talk

There is huge, untapped storytelling potential in being able to engage both the right and left brain simultaneously. One way of doing so: offer both a focused and a peripheral view. This is one of the things that made printed comics (and print newspapers) engaging. We have largely lost this on digital formats, and it is an especially acute problem on mobile, where we are forced into linearity. 

Nick suggested one solution may be to refuse the medium. If mobile does not afford the sort of storytelling you want to achieve, don't try to shoehorn your story into an inappropriate format. For example, the discussion at the Malofiej conference strongly suggests designers believe VR to be the format that finally, once again, expands our viewport to afford more right-brain experiences. 

More fundamentally, Nick's view challenges the idea of universal publishing (i.e. that our stories can and should be on all platforms) by suggesting that certain storytelling and certain platforms are simply incompatible. I think that is correct. The stance taken in pursuing universal publishing is to say that we will optimise for certain platforms that are important to us (generally for business rather than storytelling reasons), and we don't care that you get a sub-optimal (but to our mind still 'good enough') experience other platforms.

It is a fine tightrope to walk. The more platforms you optimise for, the higher the cost of production (and that relationship is likely exponential rather than linear). That cost can only be lowered by template-ising and standardising what you produce but you then run the risk of being not good enough on *any* platform, even the ones you optimise for. Because acrosss every platform, you are competing against people who are devoting the entirety of their resources and effort to make something outstanding specifically for that platform.

##NICAR

You can find a comprehensive collection of NICAR slides and tip-sheets [here](http://blog.chryswu.com/2016/03/08/nicar16-slides-links-tutorials-resources/)

*Thursday*

####What time, patience and a little OCD can teach you

There has been a clear evolution in how we are thinking about interactivitiy and its uses. There is now a much stronger sense that:

1. In most cases a directed narrative is better than just throwing open a database for people to explore

2. When trying to provide a directed narrative, most of the time you don't need or want heavy interactivity from the user. See Jessica Hullman on cognitive cost of transitions, or Archie Tse's first rule, from Malofiej:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Rules for visual storytelling (2016 edition), by <a href="https://twitter.com/archietse">@archietse</a> at <a href="https://twitter.com/hashtag/malofiej24?src=hash">#malofiej24</a> <br>c <a href="https://twitter.com/hashtag/NICAR16?src=hash">#NICAR16</a> <a href="https://twitter.com/hashtag/nnip?src=hash">#nnip</a> <a href="https://twitter.com/ctdata">@ctdata</a> v <a href="https://twitter.com/brianboyer">@brianboyer</a> <a href="https://t.co/QvlYJNQUZf">pic.twitter.com/QvlYJNQUZf</a></p>&mdash; urbandata (@urbandata) <a href="https://twitter.com/urbandata/status/708280139289862144">March 11, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

3. Scroll can be powerful. See Lena Groeger on the 'rhetorical scroll' in her [Malofiej talk](http://bit.ly/malofiej24) 

4. The only clear-cut case where throwing open a dataset for exploration makes sense is personalisation; if the user can look up something about him/herself in it

5. We haven't yet cracked how to use interactivity to promote empathy: to get readers to care about other peoples' stories. By 'we' I primarily mean news media, because *The Last of Us*, *That Dragon, Cancer*, *Her Story* etc etc etc 

6. Another situation where interactivity makes sense is if we can create meaningful interaction and trust between user and computer. Examples of this would be quizzes at simplistic end of the spectrum, and chat bots that pass the Turing test at sophisticated end. See Gregor Aisch's [lightning talk](http://slides.com/drivenbydata/nicar16#/) for more on this

####Elections API (plus the last bit of Algorithmic accountability)

Slides [here](https://docs.google.com/presentation/d/1catL1YWPEKgAGDI7BX5bZnUsPQT5WE5b9cJj1XDZZW8/pub?start=false&loop=false&delayms=5000&slide=id.g10d5b0ccf7_3_0)

####Stealth project management

There are many people who have taken on *de facto* project management roles in newsrooms. Very few are recognised for their work or their skills, and few are given the authority to better carry out that work. There is huge hunger for community and knowledge sharing.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">How digital project management actually works when not oversimplified: <a href="https://twitter.com/hashtag/nicar16?src=hash">#nicar16</a> <a href="https://t.co/dAyoDgWy0d">pic.twitter.com/dAyoDgWy0d</a></p>&mdash; AmyJo Brown (@amyjo_brown) <a href="https://twitter.com/amyjo_brown/status/708079233126404096">March 10, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
<br>

####VR interactives with Three.js

[Walktrhough on Github](https://github.com/datadesk/vr-interactives-three-js)

******

*Friday*

####Broadcast deep dive

Complex data visualisations do not work on screen. What works are people, confrontation, 'voice', and clear contrasts. This means there is separation of the 'back end' of the data journalism (which could be very complex and rigorous) and the 'front end' of what ends up on the screen. For most TV journalism, the data work is primarily done to kick off and inform shoe-leather reporting.

One very good discipline: TV reporters are told that just because they have the numbers or even the incriminating documents, they *do not* have a story until they have the people (and the tape).

####How should news app teams respond to era of distributed news

Etherpad [here](https://public.etherpad-mozilla.org/p/opennews-2016-NICAR-conversations-distributed-news)

####Data journalists and data teams

####Reverse engineering campaign finance stories

Slides [here](https://docs.google.com/presentation/d/1sZ6ZK8SuvlGrORK3JNHpvyy1meLXsOniIJvmhjqvsPk/pub?start=false&loop=false&delayms=3000&slide=id.p)

####Lightning talks

Slides [here](http://blog.chryswu.com/2016/03/08/nicar16-slides-links-tutorials-resources/#zap)

******

*Saturday*

####Let's talk leadership

Very good session. Etherpad [here](https://public.etherpad-mozilla.org/p/opennews-2016-NICAR-conversations-leadership)

####The best admin tools for the job

If you are working outside the very strict contraints of the main content management platform (i.e. by essentially designing and making your own microsites on a separate server), then even if you have templates and are standardising your production, updating individual pieces of content with site-wide CSS changes when your entire site does a redesign is just going to be hard. Even the New York Times haven't solved this problem yet.

####Life cycle of a news app

We should be thinking about lifecycles of more than just interactive news apps. What is the lifecycle of a story? a coverage topic? As for how to manage end-of-life gracefully: The biggest thing you can do is to have a plan for it

####Command line graphics

Slides [here](http://bit.ly/clgfx-nicar16)

####Snackable and shareable dataviz

Data visualisations tailored to the platform works better than viz that aren't. For most social platforms (twitter, snapchat etc) the key is to keep the message simple. Headline text is precious and should convey the main point.