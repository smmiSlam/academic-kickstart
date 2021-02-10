+++
title = "Summary on Universal Intelligence by Legg & Hutter"

date = 2021-02-05T00:00:00
lastmod = 2020-02-10T00:05:05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Summary", "CSE6369"]
summary = "This is my summary of the excellent attempt of Shane Legg and Murcus Hutter to present a formal definition of Machine Intelligence."

[header]
image = ""
caption = ""

+++

# Introduction

In this post I have tried to point out the key ideas presented in the amzing paper **Universal Intelligence: A Definition of Machine Intelligence** by *Shane Legg* and *Murcus Hutter*. Anyone looking for a quick recap on this lenghty paper to refresh his/her momeroy on the definition of machine intelligence would be an ideal audience. 

This is part of a paper review assignment of the course **CSE6369**.

Thank you for taking the time to read this article! :heart:



# My Summary

> **Intelligence Measures an Aagent’s Aability to Achieve Goals in a Wide Rrange of Environments.**

This paper takes a very thorough and systematic approach to define a robust, mathematical definition of **Intelligence** in general. The authors have weighed most prevailing views on both human intelligence and machine intelligence by referencing prevalent definitions collected from key researchers and philosophers in the relevant areas. Then, they have proposed their own formal definition with clearly pointed out similarities and dissimilarities with the gathered references. Though they have started their discussion with human or in general biological intelligence, the ultimate goal of this paper was to reach a definition for **Machine Intelligence** which has the property of being universal, mathematical, unbiased, practical and objective in nature.

The earlier phase of this paper, which deals with the definition of biological intelligence, seems more like a excellently written literature review or background study to me. This section provides us with the necessary properties and requirements to springboard into the realm of machine intelligence. The section with the formal and mathematical definition of machine learning was particularly very inspiring to me. Their definition covers the following key points-

- Interaction between an active environment and an active agent through perception and action.
    - Perception consists of two signals. Observation and Reward. This is relayed by the environment to the agent.
    - Action is what the agent decides to do (with or without previous observation-action-reward history). This is relayed from the agent to the environment.
- The definition considers the utility between short-term rewards and long-term rewards with the use of a simple discount factor raised to the power of time-step ![equation](https://latex.codecogs.com/gif.latex?%5Cgamma%20%5Ei%20r_i)
    - Later, they introduced the near-harmonic or quadratic discount factor ![equation](https://latex.codecogs.com/gif.latex?1/%7Bi%5E2%7D) which has the property of forcing the total reward to be finite and by weighing reward at different points in future differently i.e. invoking temporal preference.
- However, the most interesting inclusion was the possibility of  weighting rewards from different environments with varied complexity with the help of some sort of environment complexity measurements. Here, Kolmogorov complexity measurement is used for that purpose.
    - To incorporate the theorem of **Occam’s Razor** which states that `Given multiple hypotheses that are consistent with the data, the simplest should be preferred`, the definition is modified to include a priori probability across all possible environments, where simpler environments are much more likely to occur than the complex ones. The prior probability used here is the Algorithmic Probability Distribution which is basically the fact that each added bit to the Kolmogorov complexity increases the possible state by a factor of two hence reducing the environment probability by half.

Considering all the above facts, the final form of the definition is 

![equation](https://latex.codecogs.com/gif.latex?%5CUpsilon%20%28%20%5Cpi%20%29%20%3D%20%5Csum_%7B%5Cmu%20%5Cepsilon%20E%7D%202%5E%7B-K%28%5Cmu%29%7D%20V_%7B%5Cmu%7D%5E%7B%5Cpi%7D)

Where
![equation](https://latex.codecogs.com/gif.latex?V_%7B%5Cmu%7D%5E%7B%5Cpi%7D%28%20%5Cgamma%20%29%20%3D%20%5Cfrac%7B1%7D%7B%20%5CGamma%20%7D%5Cbold%7BE%7D%20%28%5Csum_%7Bi%3D1%7D%5E%7B%5C%20%5Cinfty%20%7D%20%5Cgamma%5Ei%20r_i%29)

and the authors call this the Universal Intelligence.


# Critical Confusion

This is the point I had some difficulties to wrap my mind around, so I am making a small note here.

The final formula of the universal intelligence is about the weighted sum of the discounted reward of all possible tasks. But, should all possible task get equal weight? Tasks that we rarely encounter (say a Rat trying to drive a car!) should not have as much importance compared to some other task everyday task (a rat trying to run from a cat :(). That is because these weird/rare/out of pattern/random tasks are so improbable to happen that being successful/failure on them does not impact much or at all on the intelligent measurement. Key thing to note here is that by complexity we are not talking about the physical/intellectual difficulty of these tasks. 

We can think of any arbitrary rules (refer to the independence of turing machine at section 3.3, page 23) to describe the tasks. And within that fixed rule, the task that requires more instructions to be completed, has the higher complexity. This is the definition of Kolomogorov Complexity of an task/environment.

The authors here used the Kolomogorov complexity to distinguish between rare/highely improbable to happen/random tasks from the more common/within pattern ones. As the Kolomogorov Complexity for rare tasks would be considerably higher than the common tasks, the inverse relation between the intelligence and complexity (i.e. rarity) in the final equation adjusts the weighting scheme acording to our common intuition.



# Ending Thoughts

As much as I am amazed by this paper, I would also like to point to the fact that the proposed equation though elegant and robust from a mathematical point of view, might struggle to deal with an open world situation where the possible number of different environments of varied complexity can be a humongous number if not infinite. Hence, within a confined and restricted virtual environment this mathematical definition might be quite successful, but the applicability of this definition within an open world might not be very acceptable.


# Further Reading List
- [Kolomogorov Complexity Measurement](https://en.wikipedia.org/wiki/Kolmogorov_complexity)
- [AIXI](https://en.wikipedia.org/wiki/AIXI)
- [C-Test](https://arxiv.org/abs/1412.8529)



# Useful Links

I have used the following websites to write the equations and make other things happen:
- [CodeCogs](https://codecogs.com/latex/eqneditor.php)
- [Sciweavers](http://www.sciweavers.org/free-online-latex-equation-editor)
- [Markdown Guilde](https://about.gitlab.com/handbook/markdown-guide/)
