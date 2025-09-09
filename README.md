# Programming-Assignment-2
This repository contains the Programming Assignment #2 solutions which includes the code for each of the problems. This Programming Assignment #2 focuses on the usage of the Numphy Library
and to be able to apply and use it on different codes and functions in creating a Python Program.

# Problem #1 - Normalization Problem

<img width="828" height="486" alt="image" src="https://github.com/user-attachments/assets/1ef29aac-2778-4870-a370-b6897c72e94c" />

Normalization is one of the most basic preprocessing techniques in data analytics. In this programming problem, the students were tasked to create a 5x5 ndArray and store it on variable X to which it will become X_normalized.

Numpy Library (alias np) allows array creation and mathematical operations which is why it is added.

np.random.seed allows random seed generation and to make the code consistent meaning, the seeds does not change everytime it runs and stays at a constant value.

np.std(s_random) calculates the standard deviation of all of the values of s_random array to which it is then stored on the variable std_s

np.mean(s_random) calculates the average or the mean of all of the values in s_random array and which is then stored on the variable mean_s

* s_norm = (s_random - mean_s) / std_s

