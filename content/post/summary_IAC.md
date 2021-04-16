+++
title = "Summary on Intrinsic Motivation Systems for Autonomous Mental Development by Pierre-Yves Oudeyer et. al."

date = 2021-02-10T00:00:00
lastmod = 2020-04-16T00:05:05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Summary", "CSE6369", "Model"]
summary = "This is my summary of the awesome paper titled as 'Intrinsic Motivation Systems for Autonomous Mental Development'."

[header]
image = ""
caption = ""

+++

# Introduction

In this post I have tried to point out the key ideas presented in the paper **Intrinsic Motivation Systems for Autonomous Mental Development** by *Pierre-Yves Oudeyer* et. al. Anyone looking for a quick glimps on models about intrinsic motivation, would be an ideal audience. 

This is also part of a paper review assignment of the course **CSE6369**.

Thank you for taking the time to read this summary! :heart:



# Summary of the Paper

Let us assume an agent embedded within an environment where there exists a set of different tasks varied in their learning complexity. This agent can explore the world freely, but since the tasks it can do varies in difficulty, it is key for the agent to choose the right task to learn at the right time.

Here the basic idea is to seprate the sensory inputs into meaningful regions so that the agent can learn each one of them separately. And to decide which region to learn first, the agent can pick the region where it has made consistant learning progress in near past.



# Ending Thoughts

- The paper presents a very good way to capture intrinsic motivation. But, the number of regions can grow exponentially when the environment is very complex. I think the proposed method might suffer in such envionments.

{{< figure src="/img/world_models_memory.png" title="Future work.  " numbered="true" lightbox="true" width="75%">}}


# Further Reading List
- [World Model](https://github.com/smmiSlam/academic-kickstart/edit/master/content/post/summary_world_models.md)

