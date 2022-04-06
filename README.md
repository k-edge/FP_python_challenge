# FP_python_challenge
coding challenge for python programmer

## Thank you for taking the time for this challenge.

A common task we are dealing with is generating multiple features from data according to some rule engine.

Write a program that receives a file with features (*.csv), and a dictionary with information on windows for rolling window operations.

an example for the Dictionary: keys will always be the same but the windows might change\

{“Average”: [ 200, 300],\
 “Standard_deviation”: [ 100, 300],\
“Exponential_average”: [ 500,700]]
}


Your task is to create these features for the data in the csv file, and returns a *.csv file with original and new features.

** If you need to make a decision regarding implementation please make the call and write why you made the decision you made.

** Time is of the essence so we would like the program to generate those features in parallel. Yet, keep in mind that this should be done on a single machine with 4 CPUs and 16 G of memory.

** We will test your code with a large dataset!

## Bonus – describe (NOT PROGRAM) how would you package this as a service
