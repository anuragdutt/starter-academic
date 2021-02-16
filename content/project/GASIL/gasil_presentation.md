

Multi-Agent Learning in Generative

Adversarial Self Imitation Learning

MA-GASIL

Anurag Dutt, Pratyush Ranjan





Introduction

● Imitation Learning - the agents learns from labeled/good examples,

imitates a better agent.

● Self imitation learning is when agent imitates itself, by training on the

past good trajectories.

● Generative-Adversarial networks - The Generator tries to fool the

Discriminator, Learning succeeds when the Discriminator cannot

differentiate the “real” and the “fake or generated” labels.

● The “fake” data is now from the same distribution as the “real” data.





Motivation

● In a recent paper, GASIL showed promising result over the GAIL.

● We implemented GASIL for multi-agent scenario.

● Predator and Prey compete with each other,

○ the predator learns on GASIL model

○ The prey learns on DDPG model

● As the model learns, GASIL wins over DDPG → predator hunts prey.

● We show that the GASIL outperforms DDPG.

● **We also experiment with - Model based GASIL (don’t have**

**results yet)**





Related Work

**GAL** - In GANs, a discriminator is trained to discriminate whether a given sample

is drawn from data distribution or model distribution. A generator (i.e., model) is

trained to “fool” the discriminator by generating samples that are close to the real

data.

**Reward Learning** - true reward function may not be optimal or even known,

GASIL learns a discriminator which acts as an internal reward function that the

policy should maximize.

**Self Imitation Learning**- directly from the past experience by retrieving similar

states in the past and choosing the best action made in the past. GASIL directly

learns to imitate past good trajectories without learning a generative model. GASIL

can be viewed as a generative adversarial extension of self-imitation learning





Approach





Approach

● Updating good trajectory buffer - GASIL maintains a good trajectory buffer B

of the trajectories that achieved high reward in the past.

● Updating discriminator (D) and policy (P) - he agent learns to imitate good

T

trajectories contained in the good trajectory buffer B using generative

adversarial imitation learning.





Experimental Results

**7 Million Episodes, ~ 1 Million Episodes Per Day, 1 Week Training**





Experimental Results

● Less than 20%: Prey Win, Predator

Loses

● Around 50%: Both Prey and

Predators are equally good.

● **Greater than 80%**: Predator Wins,

Prey Loses.





Results and Conclusion

\1. Till 500K episodes, the predator is not able to catch the prey <5% of time.

\2. After 600K episodes, the predator is able to catch prey 60% of the time

\3. After 2 Million episode, the predator is able to catch prey 90% of time.

\4. The predator shows a consistent high hunt rate after 2 million episodes. >

90%

**Conclusion:** The MAGASIL model with Independent Learned Agents

outperforms the DDPG Model.





Future Work

Things we are working on -

\1. Model Based GASIL - added improvement where the model is learnt after

a certain number of episodes, the model is then used to evaluate policies

by simulating rewards.

\2. Multi-Modal GASIL - GASIL implementation with multiple policy

distributions, is learned separately as a “skill” and applied for higher

rewards.

