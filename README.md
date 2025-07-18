Custom Pseudorandom Number Generator (PRNG) Analysis :
Table of Contents
Introduction

Algorithm Overview

Implementation Details

Visual Analysis

4.1 Scatter Plots

4.2 Histogram Analysis

Statistical Summary

Comparison with NumPy PRNG

Conclusion & Learning Outcomes

References

Appendix: Source Code

1. Introduction
This project explores the implementation of a Custom Pseudorandom Number Generator (PRNG) using the Linear Congruential Generator (LCG) algorithm. The generator’s performance is analyzed and compared to NumPy’s uniform random number generator to assess uniformity, distribution quality, and statistical properties.

2. Algorithm Overview
The LCG algorithm generates random numbers using the formula:

3. Implementation Details
Language: Python 3

Libraries: NumPy, Matplotlib

Parameters Used:

Multiplier (a) = 1664525

Increment (c) = 1013904223

Modulus (m) = 2³²

Seed (X₀) = 42

4. Visual Analysis
4.1 Scatter Plots
Two scatter plots were generated:

Custom PRNG (LCG) output in 2D

NumPy uniform generator for comparison

(Insert scatter plot images here)

4.2 Histogram Analysis
Histograms for X and Y values were plotted to evaluate distribution uniformity.

(Insert histogram images here)

5. Statistical Summary
Generator	Mean (X)	Std Dev (X)	Mean (Y)	Std Dev (Y)
Custom PRNG	0.XXX	0.XXX	0.XXX	0.XXX
NumPy Uniform	0.XXX	0.XXX	0.XXX	0.XXX

(Replace XXX with actual values from your code output)

6. Comparison with NumPy PRNG
Custom PRNG shows good uniformity but may exhibit subtle correlations.

NumPy PRNG demonstrates better randomness quality, validated by statistical tests.

7. Conclusion & Learning Outcomes
Implemented a Linear Congruential Generator for random number generation.

Compared its statistical properties with NumPy’s uniform generator.

Learned to evaluate randomness using visual analysis and summary statistics.

8. References
Knuth, D. E. The Art of Computer Programming, Volume 2: Seminumerical Algorithms.

NumPy Documentation: https://numpy.org

9. Appendix: Source Code
(Insert the full Python script here with proper formatting)

