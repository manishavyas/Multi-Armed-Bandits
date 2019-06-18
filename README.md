# Multi-Armed-Bandits and Contextual Bandits

With the use of A/B Testing, two major challenges are faced by the online subscription industry today, i.e., to maximize conversions of trial users while testing product variants and to address ever changing user preferences. 

This project involves performance evaluation of Multi-armed Bandit Algorithms, as alternatives to conventional A/B testing, that balances exploration and exploitation during the learning process to quickly identify the overall winning feature variant. 

Contextual Bandit Algorithms are also explored to predict what works best for a given user based on their attributes. This approach helps optimize the conversion rate and support personalization at the user level. 


## Multi-Armed Bandits Overview
Multi-Armed Bandit (MAB) problem  is a problem in which fixed set of resources are allocated between competing alternatives in a way that maximizes their expected  gain, when each alternatives gain is not known at the time of allocation and may become clearer with the passing time.

In MABs, an agent simultaneously attempts to acquire new knowledge ("exploration" phase) and optimize their decisions based on existing knowledge ("exploitation" phase). It attempts to balance these competing tasks in order to maximize their total value.​

It's a classic reinforcement learning problem where we strive to achieve a balance between exploration and exploitation.  If we only explore then we lose out on winning rewards and end of wasting resources and if we only exploit, we are unable to identify options which perform better in the future.

There are many practical applications of multi-armed bandits such as clinical trials, website optimization, adaptive routing in networks, financial portfolio design and many more.
