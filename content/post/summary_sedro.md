+++
title = "Summary on Simulated Environment for Developmental Robotics (SEDRo)"

date = 2021-03-26T00:00:00
lastmod = 2020-03-26T00:05:05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Summary", "CSE6369", "Environment"]
summary = "This is my summary of the paper Simulated Environment for Developmental Robotics (SEDRo) by Aishwarya Pothula el. al."

[header]
image = ""
caption = ""

+++

# Introduction

In this post I have tried to summarize the key points of the paper Simulated Environment for Developmental Robotics (SEDRo) by Aishwarya Pothula el. al. Here the authors have presented a simulated environment that can provide human like experiences. For people who are looking for a means to train human-like AI in a low-cost environment would be an ideal audience.

This is part of a paper review assignment of the course **CSE6369**.

Thank you for taking the time to read this article! :heart:


# My Summary

Developmental Robotics presents a nice a way to grow a robot from the very early stage of development. This can significantly have reduce the requirement of existing knowledge and assumptions for the learning models. Also, 


A simulated environment is better than physical environment setups on the following aspects,

- Low cost setup and maintainance of the experimental environment

- Reproduceable experiments: Experiments conducted in the physical environment is very hard to control and reproduce. Take weather forcast for example, it is nearly impossible to predict the weather with 100% accuracy even with the fastest computers. A digital computer can only handle a finite number of parameters, where in nature or physical world we have an endless number of parameters.
 
- Independence from physical time-line: Take a human infant for example. It takes years before a human infant can perform intelligent tasks, because we human are bound by our biological body and the natural flow of time. When a robot is trained in the physical environment it is bound by the same natural flow of time. However, if we can port the agent to a simulated environment, we now would have CPU clock time. This can run all the experiments and learning episodes that much faster.


Apart from being a simulated environment SEDRo facilitates the following key attributes which are essential for human-like AI training.

- Human like expereinces: This is the most significant contribution of SEDRo in my opinion. Exposing the agent to the experiences that a average human infant goes through can very useful to follow the developmental trajectory of human.

- Open-ended task: SEDRo presents experiments which do not have any specific instructions, rules or rewards.

- Longitudinal learning: The experimental observations of SERDo is presented in such a way that an agent would have to master an earlier level task to get access to the subsequent tasks. The agent's body itself would go through continuous development. Hence a task that was may be impossible for a young agent due to physical and sesory limilations, might be attainable in the later phases as the associated constraints are eased. This whole process would allow curriculum learning that can expedite learning of advanced tasks with the help of learning several basic tasks first.



# Ending Thoughts
Shifting from the physical environment towards simulated environment that tries to mimic human experience is a nice idea over all. However, SEDRo is quite limited in terms of the diversity of the available experiences. Also modelling a mother character itself can be quite complicated as well.


# Further Reading List
- [Embodied AI](https://en.wikipedia.org/wiki/Embodied_cognition)
- [Longitudinal Development](https://en.wikipedia.org/wiki/Longitudinal_study)
- [Open-ended Learning](https://thehomeschoolscientist.com/open-ended-learning-resource/)
