# Naturalistic Variation in Goal-Oriented Dialog datasets

## Motivation
Existing benchmarks used to evaluate the performance of end-to-end neural dialog systems lack a key component: `natural variation present in human conversations`.  
  
Most datasets are constructed through crowdsourcing, where the crowd workers follow a fixed template of instructions while enacting the role of a user/agent.

This results in _straight-forward, somewhat routine, and mostly trouble-free_ conversations, as crowd workers do not think to represent the full range of actions that occur naturally with real users. 


## Datasets
This directory contains the new and more effective testbeds for bAbI dialog task 5 and Stanford Multi-Domain datasets, which incorporate naturalistic variation by the user.

We observe that there is a significant drop in performance (more than 60% in Ent. F1 on SMD and 85% in per-dialog accuracy on bAbI task) of recent state-of-the-art end-to-end neural methods such as BossNet and GLMP on both datasets.

#### bAbI dialog task
The updated test sets for bAbI dialog task follow the same data format as the original dataset explained here: https://research.fb.com/downloads/babi/  

The train, validation and original test files for bAbI dialog task 5 are available at the link mentioned above.

#### Stanford Multi-Domain Dataset (SMD)
The updated test set for Stanford Multi-Domain Dataset (SMD) dataset follows the same data format as the original dataset explained here: https://nlp.stanford.edu/blog/a-new-multi-turn-multi-domain-task-oriented-dialogue-dataset/

The train, validation and original test files for Stanford Multi-Domain Dataset (SMD) are available at the link mentioned above.
