# Programming-Assignment-2
This repository contains the Programming Assignment #2 solutions which includes the code for each of the problems. This Programming Assignment #2 focuses on the usage of the Numphy Library
and to be able to apply and use it on different codes and functions in creating a Python Program.

# Problem #1 - Normalization Problem

<img width="828" height="486" alt="image" src="https://github.com/user-attachments/assets/1ef29aac-2778-4870-a370-b6897c72e94c" />

Normalization is one of the most basic preprocessing techniques in data analytics. In this programming problem, the students were tasked to create a 5x5 ndArray and store it on variable X to which it will become X_normalized.

* s_norm = (s_random - mean_s) / std_s - the formula for normalization

Numpy Library (alias np) allows array creation and mathematical operations which is why it is added.

np.random.seed allows random seed generation and to make the code consistent meaning, the seeds does not change everytime it runs and stays at a constant value.

np.std(s_random) calculates the standard deviation of all of the values of s_random array to which it is then stored on the variable std_s.

np.mean(s_random) calculates the average or the mean of all of the values in s_random array and which is then stored on the variable mean_s.

print () shows both results (normalized and randomized array) which is required to the given. This would also organize the values when it is being run.


# Problem #2 - Divisible By 3

<img width="608" height="484" alt="image" src="https://github.com/user-attachments/assets/ed8de62f-78d6-4274-844b-17f5c442ed96" />

Divisible by 3 problem consists of numbers and elements that are divisible by 3.

digit = np.arange(1, 101) creates a 1-dimensional array which contains numbers from 1 to 100 and generates numbers from 1 to 100 but does not include the 101 in the generation.

box = digit ** 2 squares every number from 1 to 100 and stores them in an array for "squared values (box variable name)".

ar = box.reshape(10, 10) reshapes a 1D square array and turns them into a 2D which includes the 10 rows and 10 columns.

divisible = ar[ar % 3 == 0] creates a boolean to which it asks whether a specific element is divisible by 3 through the use of true or false array values.

np.save('div_by_3.npy', div_by_3) For the required instruction. This allows the code to run without doing the same calculation all over again, making them loaded and consistent.

print () shows both results of the array of 100 integers and the elements that are divisible by 3. This would also organize the values when it is being run.





