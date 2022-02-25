# Qhack_Quantum_Machine_Learning : Classifying existence of galaxy
## This project is about applying qunatum machine learning in the field of astronomy. We divided the galaxy image into pixcels and used each pixcel as an input data. We classified data by labeling pixcel as 1, which has an image of galaxy and labeling pixcel as 0 that does not have an image of galaxy.

## We trained our neural network model by using quantum circuit 15 from [Expressibility and entangling capability of parameterized quantum circuits for hybrid quantum-classical algorithms, arXiv:1905. 10876] (https://arxiv.org/abs/1905.10876). We used Cross Entropy as our loss function and L-BFGS algorithm for optimization. They were coded by using pytorch and torch connector provided by qiskit module.

## We aimed for accuracy to be at least 90%

##Video

[![Watch the video](https://img.youtube.com/vi/T-D1KVIuvjA/maxresdefault.jpg)](https://youtu.be/T-D1KVIuvjA)
