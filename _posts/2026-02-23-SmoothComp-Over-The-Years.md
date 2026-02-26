---
layout: post
title:  "Smoothcomp Over the Years"
date:   2026-02-23 
categories: jekyll update
---
# Smoothcomp Over The Years

## Introduction
Smoothcomp has become one of the primary platforms for organizing and registering Brazilian Jiu-Jitsu competitions around the world. Over more than a decade of operation, it has facilitated tens of thousands of events and millions of individual matches across gi, no-gi, youth, adult, masters, and professional divisions.

That scale makes it more than just a registration tool — it’s effectively a living record of modern competitive jiu-jitsu.

In this project, I explore what that record actually looks like. How has match volume changed over time? 
How many athletes are competing each year? Are certain regions or federations growing faster than others?
What does the competitive landscape really look like beneath the surface?

This first post is an overview of the data itself — a high-level look at trends, scale, and structure.
Later posts will attempt to answer different questions like 
how much does competing improve results,
can we rank athletes with ELO in the same way chess ranks players,
and can we do better than ELO,
and hopefully much more.

All analysis is based on publicly available historical match data.  While I made every effort to include all recorded events, a small number are excluded due to limited visibility or 
incomplete results, including private events and matches without a recorded winner.

---

## The Dataset (High-Level Overview)

![Monthly Volume]({{ 'assets\images\2026-02-23\fig01-total-Match-Overview.png' | relative_url }})

The chart shows the number of events and total matches by month, as well as a 12 month rolling average to show the overall trend. Both the number of competitions and the 
total number of matches have increased steadily over time. While there are predictable seasonal fluctuations, the long-term trend is clearly upward.  By the end of 2025,
Smoothcomp is hosting close to 100 events and 40,000 matches per month with no signs of slowing down.

**Takeaway:**
Brazilian Jiu-Jitsu has seen steady growth for almost a decade. Today athletes have many more events and opportunities for matches, and it only looks like it will continue to grow 
going forward. 

---

## What Skill Levels are Most Popular?

![Skill Distribution]({{ 'assets\images\2026-02-23\fig02-matches-by-skill.png' | relative_url }})

**NOTE:** This visualization includes only adult divisions. Youth belt and skill classifications are structured differently and have proven difficult to standardize reliably 
within the dataset (I'm working on it).

Matches on Smoothcomp are heavily biased towards lower skill levels.  For no-gi matches, each jump in skill level approximately cuts the total number of matches in half.
Gi matches are similar if purple, brown, and black divisions were combined like they are in no-gi.
Interestingly, black belt gi matches are much higher than brown belt matches, which has the least total matches out of any skill level

**Takeaway:**
Most competitions favor beginner skill levels.  If you are new and looking to compete, you will be competing alongside many peers at the same experience level. If the goal 
is a long competitive career with many matches, start early in beginner divisions when brackets are large and matches are easy to come by.

## Who are the biggest Federations?

![Skill Distribution]({{ 'assets\images\2026-02-23\fig03-top10-federations.png' | relative_url }})

A federation is an organizing body or promotion that manages and sanctions multiple grappling events under a shared brand, rule set, and competitive structure.
Over half of all events and matches are hosted by federations. **Grappling Industries** is by far the largest federation, hosting over 800 events in 10 years and holds the 
4th largest size of events.  **NAGA** holds the second most events and has events of very similar sizes to grappling industries. **Newbreedbjj** has the third most 
number of events, but doesn't crack the top 10 in terms of event size.

**ADCC** is a bit newer to Smoothcomp; it began hosting **ADCC** events starting in 2023. **ADCC** only hosts about 1 event per month, but the events are by far the largest 
Smoothcomp events. Excluding **ADCC** and **subleague** as front-runners, most of the larger events start to cluster around 400-600 matches per event, which appears to be about 
as many matches as will fit into a single day competition.

**Takeaway:**
Thankfully the federations with the most number of events tend to have some of the biggest events.  For many grapplers looking to compete in or watch as many matches as possible, 
these larger federations are a great option.

Keep in mind that a large number of total matches in an event doesn't mean a large number of matches *per athlete* and many events. **ADCC**, for example, will only 
give you many matches if you keep winning.

---

## How Popular Are Youth and Master Divisions? 

![Age Distribution]({{ 'assets\images\2026-02-23\fig04-matches-by-age-style.png' | relative_url }})

In youth and masters divisions, the Gi remains more popular, making up 60% and 58% of total matches for youth and masters divisions, respectively.  The adult division tips the scale slightly
in favor of no-gi, composing 52% of total matches.

### Is the Gi Dying?

![Matches by Style]({{ 'assets\images\2026-02-23\fig05-matches-by-style-month.png' | relative_url }})

Nope, it sure aint.  The gi has remained slightly more popular than no-gi since the beginning, but that gap has narrowed in the last year. This chart includes all matches regardless
of age. The previous chart showed that no-gi is slightly more popular than gi in the adult division.

---

## Limitations & Future Work

This analysis focuses on outcomes visible in competition data. Future
extensions could explore:
- Longitudinal athlete tracking
- Rank progression over time
- Match-level technical patterns
- Gym-level effects

Individual sections of this report will be expanded into standalone
analyses in future updates.

---

## Summary

Competition is not a shortcut to mastery, but the data suggests it
plays a meaningful role in athlete development. For those on the
fence, competing earlier and more consistently may provide valuable
experience—regardless of immediate results.