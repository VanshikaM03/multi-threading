# multi-threading
# Matrix Multiplication Task

## Overview
The Matrix Multiplication Task project demonstrates how to efficiently multiply multiple matrices using threads in Python. The goal is to show how threading can be used to speed up matrix multiplication tasks and to monitor CPU usage during the computation.

## Description
The project involves generating a series of random matrices and multiplying each of them with a constant matrix. This process is repeated for a specified number of times, with each multiplication operation being performed in a separate thread. The script tracks the start and end times of each thread to calculate the time taken for each multiplication.

Additionally, the project uses the `psutil` library to monitor CPU usage during the matrix multiplication process. This allows us to analyze how the CPU is utilized as the number of threads increases.

## Key Steps
1. Generate random matrices of a specified size.
2. Multiply each random matrix with a constant matrix.
3. Perform the multiplication operations in parallel using multiple threads.
4. Monitor CPU usage during the computation.
5. Plot the time taken for each multiplication operation and the corresponding CPU usage.

## Purpose
The purpose of this project is to demonstrate the benefits of using threading for computationally intensive tasks such as matrix multiplication. By parallelizing the multiplication operations, we can reduce the overall computation time and make more efficient use of the available CPU resources.

## Potential Applications
- Scientific computing: Matrix multiplication is a fundamental operation in many scientific and engineering applications, such as signal processing, image processing, and machine learning.
- Parallel computing: The project demonstrates how threading can be used to parallelize tasks and take advantage of multi-core processors.
- Performance optimization: By monitoring CPU usage, we can identify bottlenecks and optimize the performance of our code.
