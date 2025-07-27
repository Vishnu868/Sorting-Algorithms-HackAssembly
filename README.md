# Sorting Algorithms in Hack Assembly Language

> Low-level implementation and analysis of core sorting algorithms using the Hack Assembly language.

---

## Overview

Sorting algorithms are foundational to computer science. In this project, we explore and implement four popular sorting algorithms using the **Hack Assembly language**, part of the Nand2Tetris curriculum.

The aim is to gain a deeper understanding of both **sorting logic** and **low-level programming constraints**, and to analyze performance and memory behavior when implemented outside of high-level languages.

---

## Algorithms Implemented

### 1. Bubble Sort
- Compares adjacent elements and swaps if needed.
- Time Complexity: **O(n²)**
- Easy to understand, inefficient on large datasets.

### 2. Radix Sort
- Sorts based on individual digit positions.
- Time Complexity: **O(nk)** (linear for digit-based integers)
- Uses stable sorts like Counting Sort for each pass.

### 3. Merge Sort
- Divide-and-conquer method that merges sorted halves.
- Time Complexity: **O(n log n)**
- Stable but requires additional memory.

### 4. Quick Sort
- Selects a pivot and partitions around it.
- Time Complexity: **O(n log n)** average, **O(n²)** worst-case
- Efficient, in-place sort.

---

## Hack Assembly Language

This project uses the **Hack platform** from the [Nand2Tetris](https://www.nand2tetris.org/) course.

- All `.hack` files are written for use with the **Hack CPU simulator**.
- Each algorithm is built respecting the memory layout and syntax constraints of the Hack machine.

---
