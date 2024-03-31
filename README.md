# Nes-Image-Classification
Use Natural Evolution for image classification which requires no backpropagation to compare to CNN results

notes:
used single layer and reached 85% accuracy 
added a hidden layer and got up to 91 % max .
This implementation uses Pytorch 

The natural evolution black box method  are simple and dont require back propagation for the updating of weights , the algorithm creates
a population of individuals where each individual is a copy of the initialized weights with a sigma variation or perturbation. 

This problem explores solving a supervised AI problem  for understanding the algorithm but its more suited for reinforcement learning purposes
where one has to estimate gradients of expected rewards by sampling. The algorithm updates its weights based on the fitness of each individual for 
each iteraition.

sources:
https://towardsdatascience.com/introduction-to-evolution-strategy-1b78b9d48385
https://blog.otoro.net/2017/10/29/visual-evolution-strategies/
https://www.jmlr.org/papers/volume15/wierstra14a/wierstra14a.pdf
