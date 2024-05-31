# Parallelised-Strassen-Algorithm
Implementation of Strassen's Matrix  Algorithm using OPENMP, MPI and CUDA

Matrix multiplication is a crucial operation in scientific, deep learning and engineering applications, but its high computational cost (O(n^3)) limits its practicality for large matrices.

Strassen's algorithm reduces the time complexity to O(n^2.81) using a divide-and-conquer approach. However, it requires more memory and has a larger constant factor, making it less efficient for smaller matrices.

This source codes presents hybrid algorithms that combine the traditional and Strassen's algorithms to enable parallel computation of matrix multiplication using OpenMP, MPI, and CUDA. These hybrid algorithms leverage parallel computing techniques to reduce execution time.

The algorithms are implemented in C++. Experimental results are analyzed to determine the most efficient hybrid algorithm for different matrix sizes, providing insights into the performance trade-offs between parallelism and memory usage.

By exploring these hybrid approaches, we aim to optimize matrix multiplication for improved performance in real-world applications.
