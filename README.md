# Qhack_Quantum_Machine_Learning : Classifying existence of galaxy
## This project is about applying qunatum machine learning in the field of astronomy. We successfully detected galaxy with accuracy of 94% by quantum machine learning model training in quantum circuit. We divided galaxy image from NASA into pixcels and used each pixcel as an input data. We coded quantum circuit 15 by using qiskit module and this circuit is from the paper [Expressibility and entangling capability of parameterized quantum circuits for hybrid quantum-classical algorithms, arXiv:1905. 10876] (https://arxiv.org/abs/1905.10876).  This circuit 15 has high expressibility. Expressibility quantifies how circuit can express freely in Hilbert Space. This circuit is used in data embedding and quantum machine learning model training.

## We classified data by labeling pixcel as 1, which has an image of galaxy and labeling pixcel as 0 that does not have an image of galaxy.

## We used Cross Entropy as our loss function and L-BFGS algorithm for optimization. They were coded by using pytorch and torch connector provided by qiskit module.

## The accuracy of model is 94% !!

[![Watch the video](https://img.youtube.com/vi/1wNSJAcfYjo/maxresdefault.jpg)](https://www.youtube.com/watch?v=SWmo46d4fkE)


