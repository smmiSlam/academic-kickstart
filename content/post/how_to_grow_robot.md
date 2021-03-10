+++
title = "Summary on How To Grow a Robot by Mark H. Lee"

date = 2021-03-10T00:00:00
lastmod = 2020-03-10T00:05:05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Summary", "CSE6369", "Model", "Evaluation"]
summary = "This is my summary of the cahpter 11 and 12 of the book How To Grow a Robot by Mark H. Lee"

[header]
image = ""
caption = ""

+++

# Introduction

In this post I have tried to summarize the key points of the chapter 11 and 12 of the book **How to Grow a Borot** by **Mark H. Lee**. Here the author touches topics like developmental robotics, ontogenesis, collaboration between psychology, neuroscience and computer science, embodied congtition, enaction, intrinsic motivation, proximodistal and cephalocaudal development etc. For people who are looking for building an embodied AI with inspirations from the developmental trajectory of a human infant would be an ideal audience.

This is part of a paper review assignment of the course **CSE6369**.

Thank you for taking the time to read this article! :heart:


# My Summary

Here the author presents his constructivist view about building an intelligent system by mimicking the developmental trajectory of a human infant as this might lead to develop new learning algorithms and produce putative mechanisms for infant cognitive growth. The argument is that having an embodied agent to enact on its environment based on it’s experience and drives, would develop the intelligence of this AI in such a way which would be more accessible by humans (as they have gone through a similar process themselves). The reasoning, inference and knowledge representation would greatly resemble that of humans. Hence author poses this hypothesis,

> **Robots with humanlike cognitive behavior can’t be engineered by designing software, but must be developed through constructive processes of enactive cognitive growth via interactions with the body, the environment, and other agents.**

This view is similar to what Turing suggested by the possibility of “growing” a solution rather than “building” one.

> **Instead of trying to produce a programme to simulate the adult mind, why not rather try to produce one which simulates the child’s? If this were then subjected to an appropriate course of education one would obtain the adult brain. ... We have thus divided our problem into two parts. The child programme and the education process. These two remain very closely connected.**


And since we want to start from an early stage of development, thee sooner the better, which is also known as ontogenesis. The early brain would start with only a few elementary symbols grounded with sensorimotor perceptions (concrete interaction with the environment). More complex symbols can be grounded on top of it using some sort of curriculum learning.

## Lift-Constraints, Act, Saturate (LCAS)

This curriculum learning is controlled by constraints placed on the sensory and physical ability of the agent. So, at the beginning with very rudimentary perception and ability, the agent can only intake so much information from the environment. Within this limited complexity space, the agent masters the limited possible tasks and then moves on to the next level. In this next level, tasks learnt from the previous one would act as bootstrapping to acquire new skills. As the timeline progresses, the agent’s sensory and physical abilities develop in a Proximodistal and Cephalocaudal manner. The following steps are presented as a possible curriculum

- Notice familiar stimulus -> Perform appropriate action
- Notice novel event -> Direct attention to event
- Novel event is exciting -> Act toward novel event
- New experience gained -> Attempt to repeat
- Experience can be repeated -> Store the details
- Several events cooccur -> Assume connected in some way
- Novel events are rare -> Begin play activity
- Novel events are extremely rare -> Lift a constraint if possible


To evaluate an agent under this developmental trajectory, longitudinal experiments seem appropriate. These can be extracted from the studies from the Developmental Psychology on infant behaviours.


## Intrinsic Motivation

To drive the agent through different stages of development a motivation center is proposed. This motivation center should be able to handle extrinsic reward (environment generated), intrinsic reward (agent generated) or play mode (to accommodate motor babbling, exploration and discovery without goals).

Intrinsically motivated activity in the form of play behaviors (as seen in babies, infants, and older children) is a fundamental and necessary component for the development of truly autonomous intelligent agents, both human and artificial. Play is intended as a general term that covers a wide range of behaviors from early motor babbling, through solitary physical activity, to complex interactive and social scenarios.


# Ending Thoughts
I liked the LCAS algorithm and the suggested longitudinal experiemnts to evaluate the progress of an AI agent. I think that combining attention based model for the memory, intrinsic motivation from Oudeyer and some sort of predictive model might be a good idea.


# Further Reading List
- [Embodied AI](https://en.wikipedia.org/wiki/Embodied_cognition)
- [Longitudinal Development](https://en.wikipedia.org/wiki/Longitudinal_study)
