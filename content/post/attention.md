+++
title = "Summary on Attention Is All You Need by Ashish Vaswani et al."

date = 2021-04-22T00:00:00
lastmod = 2020-04-23T00:05:05
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["SM Mazharul Islam"]

tags = ["Summary", "CSE6369", "Model"]
summary = "This is my summary of the seminal paper titled as 'Attention Is All You Need'."

[header]
image = ""
caption = ""

+++

# Introduction

In this post I have tried to point out the key ideas presented in the paper **Attention Is All You Need** by *Ashish Vaswani* et al. Anyone looking for a quick glimps on this SOTA sequence-to-sequence model or a memory-refreash on previous read, would be an ideal audience. 

This is also part of a paper review assignment of the course **CSE6369**.

Thank you for taking the time to read this summary! :heart:



# Summary of the Paper

Sequence to sequence models used to be overwhelmingly dominated by RNN-based architectures where an encoder-RNN is used to encode the input sequence to produce a context. A decoder-RNN would take this context then recurrently generate the output sequence. This encoderRNN-decoderRNN based architechtures had one major shortcoming that longer sequences were very hard to encode and subsequently generate. The recurrent nature (gradient vanishing or exploding) is parhaps the main culprit behind this.

Then came the concept of "Attention", as it has access to all the intermediate hidden states from the encoder-RNN and thus have the ability to focus on a specific section of the input sequence while generating the output sequence. This mechanism dramatically increased the accuracy and stability of encoder-decoder based seq2seq models.

However, as the base RNN remains in action, such models are not very fast to train and the problem coming from the recurrent nature still persists to some extent. To solve this, our paper of interest proposes a method that depends solely on attention while completely washing off the RNN part.


# Ending Thoughts
Transformer based models are very powerful indeed as they can model the relation within a presented sequence while keeping an eye to the context. They also has this "Attention" mechanism that allows it to focus at a certain experience in past to predict the next scene (next vector). Hence, the model overall is a very good prediction mechanism. 

However, the model still is a passive learner in my opinion. It does not differentiate between situations where in one learning can be meaningful but in another learning is difficult to impossible. Currently the model relies on the brute strength of GPU and huge but random digital data, but this model would fail to meaningfully crawl through internet to gather information in a meaningful and increamental manner. This model does not supervise itself to maximize the learning by differentiating among available training data. This lack of self-supervision gives us room for further improvements in terms of learning efficiency and developing scalable learning agents.

A possible hint of this self-supervision part can be found in [this](https://smmislam.netlify.app/post/summary_iac/) paper where the learning progress through various possible learning routes are comapred and the best route is chosen to maximize the agent's average learning rate.

{{< figure src="/img/world_models_memory.png" title="Future work.  " numbered="true" lightbox="true" width="75%">}}


# Further Reading List
- [Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- [Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html)
- [Sequence to Sequence model (translation)](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/)
- [Minimum GPT](https://github.com/karpathy/minGPT)

