# TF2.0_Keras_DDPG
A commented Tensorflow 2.0 Keras implementation of DDPG for open AI gym continuous environments.

This implementation of Deep Deterministic Policy Gradient is different from other implementations 
only in that regard, that I kept to keras only style, meaning that also the somewhat complicated
loss function is implemented by keras type custom loss mehtods.

I did this for learning and undestanding only. It is most closely to the OpenAi Spinning up explanation
and thier implementation: 
https://spinningup.openai.com/en/latest/algorithms/ddpg.html
https://github.com/openai/spinningup/blob/master/spinup/algos/ddpg/ddpg.py

TODO: Currently it does not apear to converge in any of the tested envs but did not test for long. 
Could be only HP optimization problem but can't gurantee.
