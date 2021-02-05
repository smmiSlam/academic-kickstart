+++
title = "Summary on Universal Intelligence by Legg & Hutter"

date = 2021-02-05T00:00:00
lastmod = 2020-02-05T00:05:05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Summary"]
summary = "This is my summary of the excellent attempt of Shane Legg and Murcus Hutter to present a formal definition of Machine Intelligence."

[header]
image = ""
caption = ""

+++

# Introduction
In this post I have tried to point out the key ideas presented in the amzing paper "Universal Intelligence: A Definition of Machine Intelligence" by Shane Legg and Murcus Hutter. Anyone looking for a quick recap on this lenghty paper to refresh his/her momeroy on the definition of machine intelligence would be an ideal audience. 

This is part of a paper review assignment of the course CSE6369.

Thank you for taking the time to read this article! :heart:


# My Summary
This paper takes a very thorough and systematic approach to define a robust, mathematical definition of “Intelligence” in general. The authors have weighed most prevailing views on both human intelligence and machine intelligence by referencing prevalent definitions collected from key researchers and philosophers in the relevant areas. Then, they have proposed their own formal definition with clearly pointed out similarities and dissimilarities with the gathered references. Though they have started their discussion with human or in general biological intelligence, the ultimate goal of this paper was to reach a definition for “Machine Intelligence” which has the property of being universal, mathematical, unbiased, practical and objective in nature.

The earlier phase of this paper, which deals with the definition of biological intelligence, seems more like a excellently written literature review or background study to me. This section provides us with the necessary properties and requirements to springboard into the realm of machine intelligence. The section with the formal and mathematical definition of machine learning was particularly very inspiring to me. Their definition covers the following key points-

- Interaction between an active environment and an active agent through perception and action.
    - Perception consists of two signals. Observation and Reward. This is relayed by the environment to the agent.
    - Action is what the agent decides to do (with or without previous observation-action-reward history). This is relayed from the agent to the environment.
- The definition considers the utility between short-term rewards and long-term rewards with the use of a simple discount factor raised to the power of time-step (lambad^i).
    - Later, they introduced the near-harmonic or quadratic discount factor (1/i^2) which has the property of forcing the total reward to be finite and by weighing reward at different points in future differently i.e. invoking temporal preference.
- However, the most interesting inclusion was the possibility of  weighting rewards from different environments with varied complexity with the help of some sort of environment complexity measurements. Here, Kolmogorov complexity measurement is used for that purpose.
    -To incorporate the theorem of “Occam’s Razor” which states that “Given multiple hypotheses that are consistent with the data, the simplest should be preferred.”, the definition is modified to include a priori probability across all possible environments, where simpler environments are much more likely to occur than the complex ones. The prior probability used here is the Algorithmic Probability Distribution which is basically the fact that each added bit to the Kolmogorov complexity increases the possible state by a factor of two hence reducing the environment probability by half.

Considering all the above facts, the final form of the definition is 
Y(pi) = Sum(2^-K(mu) V_mu^pi), V_mu^pi = 1/C E(sum(discount_factor*reward))
 and the authors call this the Universal Intelligence.
 
 
