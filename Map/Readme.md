# 🗺️ Map Data Structure Implementation

**Course Project – UC Berkeley CS88C**

## Overview

This project implements a custom **Map (key–value dictionary) data structure** from scratch in Java.

A Map stores pairs of keys and values and allows efficient insertion, lookup, and deletion of elements. The goal of this project was to understand how associative containers work internally by implementing them without using built-in libraries.

Several map implementations were developed and compared in terms of **performance and time complexity**.

---

## Key Concepts

This project focuses on core data structure concepts:

- **Associative Containers**
  - storing key–value pairs
  - efficient lookup and updates

- **Linked Data Structures**
  - implementing a map using linked lists

- **Binary Search Trees**
  - ordered storage of keys
  - recursive traversal and search

- **Algorithmic Complexity**
  - analyzing runtime performance of different data structures

---

## Implementations

The following map implementations were developed:

### ULLMap
An unordered linked list implementation of a map.

- Stores key–value pairs sequentially
- Simple structure but inefficient for large datasets
- Lookup requires linear time

**Time Complexity**

| Operation | Complexity |
|-----------|------------|
| Insert | O(n) |
| Lookup | O(n) |
| Remove | O(n) |

---

### BSTMap

A map implemented using a **Binary Search Tree**.

- Keys are stored in sorted order
- Enables faster search compared to linked lists
- Uses recursion for insertion and lookup

**Time Complexity (average case)**

| Operation | Complexity |
|-----------|------------|
| Insert | O(log n) |
| Lookup | O(log n) |
| Remove | O(log n) |

---

## Performance Comparison

To evaluate efficiency, randomized string keys were inserted into different map implementations and execution times were measured.

The implementations were compared with Java's built-in structures:

- `TreeMap`
- `HashMap`

This experiment demonstrates how different underlying data structures impact performance.

---

## Learning Outcomes

Through this project I gained experience in:

- implementing fundamental data structures from scratch
- designing class interfaces for key–value containers
- analyzing algorithmic time complexity
- comparing custom implementations with standard library data structures

---

## Note

Due to course policy, the full source code is not publicly available.

If you are interested in discussing the implementation details or reviewing the code, feel free to contact me.
