+++
title = "Summary on Deep Neuroethology of a Virtual Rodent by Josh Merel et. al."

date = 2021-02-26T00:00:00
lastmod = 2020-02-26T00:05:05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Summary", "CSE6369", "Model", "Evaluation"]
summary = "This is my summary of the paper titled as 'Deep Neuroethology of a Virtual Rodent'."

[header]
image = ""
caption = ""

+++

# Introduction

In this post I have tried to point out the key ideas presented in the paper **Deep Neuroethology of a Virtual Rodent** *Josh Merel et. al.*. Anyone looking for a quick glimps on this paper to refreash previous read, would be an ideal audience. 

This is also part of a paper review assignment of the course **CSE6369**.

Thank you for taking the time to read this summary! :heart:



# Summary of the Paper

> **Can a Neuroscientist Understand a Virtual Rodent**

This paper tries to facilitates grounded collaborations between deep reinforcement learning and motor neuroscience. Find connections/similarities between the behavior of a simulated intelligence and a corresponding physical entity. The four key stages are described as below:

- Design a realistic agent with features closely resembling the physical entity.
    - Data and measurements taken from real laboratory rat cadavers (Appdx 1). 38 controllable degrees of freedom. Multiple segments which are controlled by tendons that co-activate multiple joints.
    - Equipped with vision sensor (Egocentric RGB camera), Proprioceptive Sensors , Tactile sensors, Kinematics sentors.

- Train the agent on several tasks.
    - Four tasks. Gaps run, maze forage, bowl escape and two-tap.
    - Learning Model is shown in the following figure.
{{< figure src="/img/virtual_rodent.png" title="Learning model of the virtual rodent.  " numbered="true" lightbox="true" width="50%">}}

- Analysis the behavior and neural activities of the agent.
    - Agent learned to adapt similar movements in a selective manner for different tasks, suggesting that the agent exhibited a form of behavioral flexibility.
    - The feature encoding of policy networks was somewhat consistent with the emergence of a hierarchy of behavioral abstraction.
    - Up to some extent, behavioral representations are re-used. When equipped with lower-capacity learning models, animals must rely on a smaller, shared behavioral representation across tasks.
    - A nested time-scale learning model, where the core layer (low frequency) transforms sensory information into a contextual signal in a task-specific manner. This signal then modulates activity in the policy (high frequency) toward different trajectories that generate appropriate behaviors in a more task-independent fashion.
    - Overlaps with common intuition, I think. Can be analogous to the comparison between being paralyzed and autism (maybe).

- Draw possible analogies with the behavior of the corresponding physical entity.
    - The exact kinematics of the virtual rodent’s behaviors did not exactly match those observed in real rats, they did reproduce unexpected features. Stride frequency of the virtual rodent during galloping matches that observed in rats.
    - Sequential activity hints at an acknowledged mechanism for the rodent’s behavioral production.
    - The ablation study of core and policy layer seems to be intuitive.


# Ending Thoughts

- What I loved about the paper
    - This approach is very promising in the sense that it aims to explain the functionality of an AI brain in terms of biological ethology.
    - The proof of nested time-scale concept within the presented model is amazing.
- Criticism
    - Simplicity of the Experimental Setup: While watching the videos, the virtual rodent is locked onto the single task as if that is the only thing that exists in its world.
    - Simplicity of the Tasks: This model does not address the situations when there are no explicit rewards for completing a task.


# Further Reading

- [Embodied Control](https://en.wikipedia.org/wiki/Embodied_cognition)
- [Actor-Critic RL](https://theaisummer.com/Actor_critics/)
- [Representational Similarity Analysis (RSA)](https://www.sciencedirect.com/science/article/pii/B9780128120286000276)
- [Centered Kernel Alignment (CKA) index](https://medium.com/syncedreview/geoffrey-hinton-leads-google-brain-representation-similarity-index-research-aiming-to-understand-b5d14bf77f49)
