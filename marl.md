# Multi-Agent Reinforcement Learning (MARL)

A collection of papers and resources.
Another extensive collection can be found on this [GitHub page](https://github.com/LantaoYu/MARL-Papers).

Short descriptions are added step by step.
Very good, helpful resources that I recommend reading will be marked with :sparkling_heart:

## MARL Overview

These papers give a good general overview.

+ [Multiagent Systems: Algorithmic, Game-Theoretic,and Logical Foundations](http://www.masfoundations.org/mas.pdf) (2008): Good general overview on Multiagent Systems. Covers all topics concerning MAS and explains them well. From CPS, DCPS, and Distributed Optimization to Game Theory and Equilibria and it also covers Learning (eg. Reinforcement Learning and Evolutionary Learning) :sparkling_heart:
+ [Multi-agent reinforcement learning: An overview](http://www.dcsc.tudelft.nl/~bdeschutter/pub/rep/10_003.pdf) (2008): Broad overview of theoretic foundations and algorithms in the MARL domain. Mainly, the older approaches, but very good for a sound understanding. :sparkling_heart:
+ [A comprehensive survey of multi-agent reinforcement learning](http://www.dcsc.tudelft.nl/~bdeschutter/pub/rep/07_019.pdf) (): Similar to above. Not so much new info.
+ [Multi-Agent Reinforcement Learning: A Selective Overview of Theories and Algorithms](https://arxiv.org/pdf/1911.10635.pdf) (2019): Great review and theoretic background of MARL in light of new breakthroughs. Addresses recent methods and algorithms. Provides a lot of useful references/ctations. :sparkling_heart:

## Deep MARL

+ [A Survey and Critique of Multiagent Deep Reinforcement Learning](https://arxiv.org/pdf/1810.05587.pdf) (2019): Very precise, clear and extensive. Describes Deep MARL work in four different problem areas and lists main lessons learned, best practices and open challenges. References a lot of recent methods. :sparkling_heart:
+ [Deep Reinforcement Learning for Multi-Agent Systems: A Review of Challenges, Solutions and Applications](https://arxiv.org/pdf/1812.11794.pdf): (2019) Concise explanation of Deep MARL, good addition to above paper. Mainly, explains methods tackling non-stationarity and partial observability. It also mentions common MAS training schemes. :sparkling_heart:
+ [Deep multi-agent reinforcement learning](https://ora.ox.ac.uk/objects/uuid:a55621b3-53c0-4e1b-ad1c-92438b57ffa4) (2018): Dissertation from Oxford with DeepMind and OpenAI affiliations. Focuses on different Deep MARL aspects (combination of 6 or 8 papers). Talks about how agents can learn to collaborate (very interesting: about distributed experience replay but also rewerd assignment), to communicate and to reciprocate.
+ [Deep Reinforcement Learning Variants of Multi-Agent Learning Algorithms](https://project-archive.inf.ed.ac.uk/msc/20162091/msc_proj.pdf)(2016): Meh.. Discussion of two specific Deep MARL alorithms/ DQN extensions. Not much better than simple DQN, also architecture unclear (seemed to be for competitive game?) 
  

## Cooperatvie Reinforcement Learning

+ [A Review of Cooperative Multi-Agent Deep Reinforcement Learning](https://arxiv.org/pdf/1908.03963.pdf): Very extensive review and listing of deep MARLs for cooperative games. Detailed eplainations of many algorithms, and lots of useful resources. A lot on Independent Q learning, a bit on consensus. :sparkling_heart:
+ [Multiagent Cooperation and Competition with Deep Reinforcement Learning](https://arxiv.org/pdf/1511.08779.pdf) (2015): The authors play a game with two independent agents with DQN implementations and show that they start to collaborate.

### Independent Q-Learning/ Centralized Learning, Decentralized Execution

+ [Stabilising Experience Replay for Deep Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/1702.08887.pdf) (2018?): Fingerprints in Experience replay
+ Also DRUQN,DLCQN (leniency),hystereric DQN


### Consensus/ Parameter Sharing

+ eg some work by zhang, parameter sharing, DEC-HDRQN, qd learning?
  

## Deep MARL for Job Shop Scheduling

+ [Adaptive reactive job shop scheduling with reinforcement learning agents]() (Gabel, Riedmiller, 2008): They use FQN here.. that should be instable..
+ What else?



+ Not very clear but states to use deeprl, 2020: https://arxiv.org/pdf/2009.03836.pdf

+ Could be a good review, check out later: https://link.springer.com/chapter/10.1007%2F978-3-030-14347-3_34