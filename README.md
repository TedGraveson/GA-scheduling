# Genetic Algorithm for Scheduling Problems
This repository contains a implementation of a genetic algorithm applied to the permutation flow shop problem.

## Generating Data
In the dataset folder is a program for generating a set of test inputs.
To compile and run the program:
~~~
gcc job_gen.c -lm -o job_gen
./job_gen
~~~
This will generate 120 permuation flow shop problems of various dimensions.

## Running the Algorithm
Once the dataset has been generated, the Jupyter notebook can then be run cell by cell (assuming all dependencies have been installed). A valid Python installation with Jupyter, Matplotlib, and Pandas is required.

The notebook contains an example run of the algorithm, followed by the settings used for each problem instance described in the report. These may take a while to run consecutively, so one want to run them one by one.