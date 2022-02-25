# Qhack_Quantum_Machine_Learning : Classifying existence of galaxy

## This project delvoping a technique to detect of the galaxies in the telecope image via qunatum machine learning. 

We successfully demonstrated detection of galaxy with accuracy of 94% via quantum machine learning model from NASA image. We divided galaxy image from NASA into small 16x16 image as an input data. Then we encoded and train the data with quantum circuit using the parameterized quantum circuit from the paper [Expressibility and entangling capability of parameterized quantum circuits for hybrid quantum-classical algorithms, arXiv:1905. 10876] (https://arxiv.org/abs/1905.10876). With the circuit with high expressibility, we trained and test our model with Cross Entropy as our loss function and L-BFGS algorithm for optimization. This algoirthm is realized in pytorch and qiskit machine-learning module. This work show our capability of clssification of galaxy images. 

## The accuracy of model is 94% !!

[![Watch the video](https://img.youtube.com/vi/1wNSJAcfYjo/maxresdefault.jpg)](https://www.youtube.com/watch?v=SWmo46d4fkE)


