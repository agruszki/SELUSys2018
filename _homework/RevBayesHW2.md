---
title: Bayesian Methods HW2
teaching: 180
exercises: 0
questions:
- "How does a estimating a solution using a Bayesian method differ from likelihood?"
- "How does the output of a Bayesian tree search differ from that of likelihood or parsimony?"
objectives:
- "Explain what different models are telling us about evolution."  
- "How does a heuristic search differ under likelihood?"
- "Perform ML analyses using PAUP on LONI" 
---

## RevBayes Homework Two

1. In the slide move, try 5 different ranges for the slide move. Which one produces the best ESS?

delta=.01 ESS=646.6763
delta=.1 ESS=811.5084
delta=1 ESS=901
delta=10 ESS=800.2228
delta=100 ESS=783.4821

The best ESS value is 901. The slide move with a delta value closest to 1 produced the best ESS.  

2. In the slide move, try 5 different ranges for the scale move. Which one produces the best ESS?

lambda=.01 ESS=795.044
lambda=.1 ESS=901
lambda=1 ESS=901
lambda=10 ESS=901
lambda=100 ESS=738.5748

The best ESS value is 901. The slide move with a lambda value ranging from .1-10 produced this ESS value.  

3. How does using both moves change the ESS? Why does this make (or not make) sense?

If both delta and lambda are set to 100, the ESS is very low (60.9066). If both delta and lambda are set to 0.01, the ESS is also very low (5.1857). 
Combinations of these extreme values also produce low ESS scores. Delta and lambda set standard deviations from which new values of the distribution 
are drawn. A large deviation means a higher variation in the numbers drawn and a small deviation means a smaller variation in the numbers drawn. This 
makes sense because ESS values are a measure of how thoroughly explored the values are. If delta or lambda don't allow for a proper range, the ESS 
will not be high enough.  

4. What happens if you double one of the moves? For example, if you have a scale move that means the mu prime will be far from the mu, _and_ one that implies the mu prime should be really different?

If lambda is twice delta (100 and 50), the ESS is 139.8561. If the opposite is true, the ESS is similar at 151.9056.  






##Try to have this done by the end of the work week, but if it's done by the end of spring break, that's OK, too.
