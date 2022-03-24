---
layout: post
title:  "Dangers of Session-based Metrics"
date:   2022-03-23 07:00:00 +0000
categories: metrics
---

Georgi Georgiev's post [When Session-Based Metrics Lie](https://blog.analytics-toolkit.com/2022/when-session-based-metrics-mislead/) has some great examples showing how session-based metrics can lead you to wrong conclusions.

One example a former co-worker gave was:

> Our product has 2 users, John and Trevor. John (a very active user) has 5 sessions and Trevor (a less active user) has 1. 
> Each of John's sessions has 5 prompts shown and he clicks 1 of them, each of Trevor's has 2 and he clicks 1 of them.
>
> Overall, 27 prompts were shown (25 to John and 2 to Trevor) and 6 clicked (5 by John and 1 by Trevor). 
> 
> The average click rate [by suggestion] is 6÷27 ~ 22.2%
Each of John's 5 sessions had a click rate of 20%. Trevor's 1 session had a click rate of 50%. The average click rate [by session] is 25%.
>
> John's click rate was 20%. Trevor's was 50%. The average click rate [by user] is 35%.

The warning being:
> User-level metrics treat all your users equally. Each person contributes 1 number to the average. Session-level metrics treat each session equally. **More-active people contribute more to the average**.

With session-level metrics, you run the risk of letting _very_ active users be over-represented.
