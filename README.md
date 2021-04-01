# Playing with temporal abstraction for reinforcement learning

Implemented most of the methods in Between MDPs and Semi-MDPs: A framework for temporal abstraction in reinforcement learning (Richard S. Sutton, Doina Precup, Satinder Singh – Artificial Intelligence, 1999).

Experimented with transfer learning abilities of the Option-Critic Architecture (Pierre-Luc Bacon, Jean Harb, Doina
Precup - JMLR 2016), and implemented model learning for the learnt options.



## Set up (tested Mar/2021):
Python 3.8.8

gym-0.7.2 (Using other version could result to "AttributeError: Fourrooms instance has no attribute 'unwrapped'" Error)


```commandline
conda create --name HRL
conda activate HRL
conda install numpy
pip install gym==0.7.2
conda install scipy
conda install matplotlib
```
change model.py
```
#from scipy.misc import logsumexp
from scipy.special import logsumexp
```
