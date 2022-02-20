---
layout: post
title:  "Survivorship Bias in Web Performance"
date:   2022-02-20 07:52:00 +0000
categories: measuring
---

Here's a great post about the effects of page load time on how many visitors you're able to account for in your logs. 

- [Survivorship Bias in Web Performance - simonhearne.com](https://simonhearne.com/2022/survorship-bias-in-webperf/)

The gist is that there are likely _many_ visitors who give up on your site before it loads because of how slow it is for them. Since these visitors don't show up in your logs, their load times aren't accounted for - so your page is even slower than you think it is.

Thinking about Growth, I wonder how many users we're missing out on because our site is too slow to serve them? This article shows evidence ranging from 5-20% of the number of users you do account for.


Incidentally, at ExP I co-wrote a similarly themed blog post about [survivorship bias and Sample Ratio Mismatches](https://www.microsoft.com/en-us/research/group/experimentation-platform-exp/articles/diagnosing-sample-ratio-mismatch-in-a-b-testing/). The story is the same - we have to be careful about making conclusions on incomplete data and it's worth thinking a lot about what we _aren't_ able to measure.