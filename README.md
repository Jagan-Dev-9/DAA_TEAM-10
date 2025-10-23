# 🌤️ Parallel Weather Forecasting Using PRAM Algorithms 🌤️

[![Algorithm](https://img.shields.io/badge/Algorithm-Parallel%20Computation-blue.svg)](https://github.com)
[![Language](https://img.shields.io/badge/Language-Python-green.svg)](https://python.org)
[![Complexity](https://img.shields.io/badge/Time%20Complexity-O(nT%2FP)-orange.svg)](https://en.wikipedia.org/wiki/Time_complexity)
[![License](https://img.shields.io/badge/License-Academic-lightgrey.svg)]()

> **Course:** Design and Analysis of Algorithms (24CS2203)  
> **Semester:** Even Semester 2024-2025  
> **Institution:** Department of Computer Science and Engineering  

---

## 👥 Team Members

| Name               | Roll Number |
|--------------------|-------------|
| **Jagan Sunkavalli**| 2420030714  |
| **Pardheev Nalla**  | 2420090145  |

**Course Instructor:** Dr. J Sirisha Devi, Professor  

---

## 🎯 Problem Statement

Traditional weather forecasting requires processing large volumes of meteorological data with high computational complexity. This project implements **PRAM-based parallel algorithms** to divide and conquer the workload, significantly accelerating forecast generation with improved scalability and accuracy.

---

## 🧮 Algorithm Summary

- Partition atmospheric data grid among processors  
- Parallel computation of forecast model equations per data block  
- Concurrent spectral transforms (FFT) for atmospheric parameters  
- Real-time data assimilation via parallel updates  
- Ensemble forecasting by running multiple simulations in parallel  
- Aggregation of parallel results into a unified forecast  

---

## ⚡ Complexity Analysis

| Metric            | Complexity                  | Description                          |
|-------------------|-----------------------------|------------------------------------|
| Time Complexity   | O((n × T) / P) + O(log P)   | Parallel speedup & communication overhead |
| Space Complexity  | O(n + P)                    | Data storage plus processor states |


---

## ✅ Conclusion

This project demonstrates the power of PRAM parallel computation for weather forecasting, delivering faster, scalable, and accurate predictions critical for real-world applications including disaster management and climate modeling.

---

✨ **Thank you for reviewing our project!** ✨
