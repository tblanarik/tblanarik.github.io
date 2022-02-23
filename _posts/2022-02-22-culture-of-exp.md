---
layout: post
title:  "Culture of Experimentation"
date:   2022-02-23 07:00:00 +0000
categories: culture
---

I just read Stefan Thomke's 2020 [HBR article "Building a Culture of Experimentation"](https://hbr.org/2020/03/building-a-culture-of-experimentation#building-a-culture-of-experimentation).

Something that really struck me was:

> In 2015 experimentation wasn’t a core activity at IBM; the company’s IT function offered to run tests, but they were costly, were charged back to business units, and had to follow a rigid process. The testing capacity consisted of just one specialist, who was also the gatekeeper and who rejected many proposed experiments because he felt that they weren’t strong-enough candidates. As a result, the company ran only 97 tests that year.

He goes on to talk about how Ari Sheinkin pushed for, among other things, having the marketing team run 30 experiments in 30 days. The eventual cultural shift resulted in IBM runnig over 2800 experiments in 2018. 

What's not clear to me is how IBM made sure the experiments still met a minimum quality bar. Were the experiments just conceptually simple? 
Or did the center of excellence Sheinkin set up provide enormous amounts of support? 
It's not hard to end up with [unhealthy metrics](https://www.microsoft.com/en-us/research/group/experimentation-platform-exp/articles/p-values-for-your-p-values-validating-metric-trustworthiness-by-simulated-a-a-tests/), for instance.

It's natural to want to gatekeep experimentation to make sure it's done right, but now I'm wondering if that's just part of a vicious cycle of making experimentation harder, more expensive, and less successful.

Maybe the answer is in actually taking the time to set up all of the automated checks to catch most of the common issues (A/A tests, SRM checks, etc). Regardless, I like the idea of setting really aggressive goals on experiment count alone just to build the muscle.
