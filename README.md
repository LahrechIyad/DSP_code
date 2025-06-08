# DSP Project – Signal Processing in Python
### 📘 Overview
This project is part of the Signal Processing course in the GSTR 1 – Telecom department. It aims to implement and demonstrate core Digital Signal Processing (DSP) concepts using Python, specifically in a Jupyter Notebook environment.


### 🎯 Objectives
Understand and implement DSP fundamentals

Build a modular and well-documented Python codebase

Visualize and analyze DSP operations like convolution, filtering, and frequency spectra

### 🧠 Core Concepts Implemented
1. Convolution
Custom implementation using numpy.convolve

Example:

x = delta(n + 5) + 2 * delta(n - 2) - 10 * delta(n - 3) + ...
h = delta(n + 1) + delta(n) + delta(n - 1) + ...
result = convolve(x, h)


2. FFT Spectrum Analysis
Frequency and amplitude input configurable

Parameters:

frequencies = [1000, 4000]      # Hz
amplitudes = [1, 2]
fs = 20000                      # Sampling rate (Hz)
FREQ_RANGE = 80000             # Plotting range
Generates plots for both original signal and replicas using FFT

3. Filter Application
Simple low-pass filter implementation

Requires cutoff frequency Fc, e.g., Fc = 8000 Hz

Output includes filtered signal visualization


### 📝 Notes
All code is fully commented and structured for learning purposes.

The GitHub repositories of each team member host copies of this project.

Ideal for students or beginners seeking hands-on understanding of DSP concepts using Python.

