---
layout: post
title: "Kruschke Chapter 3"
date: 2012-11-05 22:26
comments: true
categories: Kruschke Bayesian statistics
---
This is the first really substantial chapter; the first two were really just a warm-up. Kruschke presents this chapter as a kind of intro to probability, but (naturally) he makes some very specific choices about what to approach and how to approach it.  A lot of it comes across as kind of foreshadowing, which makes it a little hard to follow or grasp the point of at times. Ultimately, I think this chapter should go pretty quick the first read-through, to prime some ideas, but the ideas probably won't really start to sink in until they get applied later.

Another overall comment: Kruschke points this out at some point himself, but the fact is that throughout this chapter, he's really talking about two kinds (or contexts) of probability. One is as a mathematical expression of belief, which, I assume, is pretty much a given for any kind of Bayesian analysis.  The other is the parameter (&theta;) of interest that one is trying to estimate.  I mean, in all the coin-flipping examples, there is the probability of heads, which is just a parameter of the data-generating process.  In a different kind of data or analysis, it might be something else, not probability (I'm guessing that when we get to Bayesian regression, the parameter will be something like a regression coefficient, which is not a probability). And then there's the probability (or belief) in a parameter value (*p*(&theta;)), which is always going to be expressed as probability (e.g., for regression, there should be probabilities/beliefs for different coefficient values).  As intuitive and appealing as the coin-flipping examples are, I find this double-sided discussion of probability to be kind of confusing.

So, on to the details of the chapter. Kruschke focuses on the simple case of predicting coin flips and deciding whether the coin is fair.  This has the advantage of not only being conceptually intuitive, but also numerically convenient, allowing for a variety of analytic approaches that don't require the heavier-duty computational tools of MCMC, and I'm sure this was a choice Kruschke made by design.

But illustrating my quibble above, he starts with a discussion about how the fairness of the coin (the parameter &theta;) is a probability, and this can be simulated as a long-run relative frequency, or derived mathematically, and then he switches abruptly to a brief discussion about probability as a expression of subjective belief, even discussing how one might heuristically estimate one's own internal numerical belief in something. I find this back-and-forth discussion a little disorienting, and paradoxically, it feels like he goes into too much detail and not enough detail. The discussion of "calibrating" one's subjective belief seems to invite more questions and confusions than are necessary to make the simple point that in Bayesian analysis, "belief" is represented mathematically by probabilities. But it's not quite in-depth enough to foster a deep understanding or exploration of the ideas.

I think if I were using this for a course, I would want to *either* (a) spend more time on fleshing out the ideas in this chapter, and take care to very explicitly pull apart the concepts of probability-as-parameter vs. probability-as-belief, or (b) speed through or defer sections of the chapter entirely, jump straight into some analysis, and refer back to sections in this chapter to help present the basic ideas behind the analysis.

Working through the rest of the chapter, I feel like he's foreshadowing the steps from Chapters 5 through 7, from a purely analytic approach, to a grid approximation, to MCMC sampling.  He touches on a number of interesting points, including some nice discussions of:

- probability distributions (*mass* for discrete outcomes and *density* for continuous)
- the normal probability distribution
- the relationships between mean, variance, standard deviations, and medians
- Highest Density Intervals (which, in my NHST conceptual background, are like Bayesian confidence intervals)
- two-way probabilities, marginal probabilities, and conditional probabilities. This is where he starts to lead towards the crux of Bayes's rule.


But all these things feel like sort of incomplete foreshadowing of what's to come.  Priming the pump, as it were, but I personally have a hard time retaining stuff when I don't see the point of it until later.  So again, I think in practice I would recommend zipping through and then revisiting this chapter once you've gotten into the applications later.

The other main way I can think to describe Kruschke's writing so far is that it is a very uneven flow of information.  There are stretches of very informal, easy-to-read text that glide by, and then I hit a sentence or two that quickly assert or review some equation or other point that is very dense, and I feel like I have to read it over several times and work through it in my head to make sure I'm understanding.  This is not really a criticism, just a description of my personal experience in reading.

These relatively minor worries and hand-wringings aside, I think this is a nice, concise, readable chapter.  I think he does a good job of discussing some basic concepts in probability in an extremely approachable way, in order to set up a better understanding of what's to come. It's certainly not an exhaustive treatment, but it's useful enough that I'd recommend a good reading of it, even for peole coming to the book with a decent stats background. But I really do think that most of the good points may be a little lost or unappreciated until some of the later topics in the book are broached.
