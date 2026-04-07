# A2Z Data Structure and Algorithm topics

This repository contains clean, well-structured C++ implementations of fundamental and advanced data structures and algorithms. It follows a progressive learning path starting from basic linear structures and gradually moving to more complex techniques used in competitive programming and technical interviews.

---

## 📋 Table of Contents

- [Repository Overview](#repository-overview)
- [Programming Language](#programming-language)
- [Goals & Scope](#goals--scope)
- [How to Use](#how-to-use)
- [Contents](#contents)
  - [1. Pre-computation Techniques](#1-pre-computation-techniques)
  - [2. Linked List](#2-linked-list)
  - [3. Stack and Queue](#3-stack-and-queue)
  - [4. Sorting Techniques](#4-sorting-techniques)
  - [5. Subset Generation](#5-subset-generation)
  - [6. Binary Search](#6-binary-search)
  - [7. Binary Tree](#7-binary-tree)
  - [8. Binary Search Tree](#8-binary-search-tree)
  - [9. Heap](#9-heap)
  - [10. Policy-Based Data Structures](#10-policy-based-data-structures)
  - [11. Graph](#11-graph)
  - [12. Trie](#12-trie)
  - [13. Ternary Search](#13-ternary-search)
  - [14. Dynamic Programming](#14-dynamic-programming)
  - [15. Sparse Table](#15-sparse-table)
  - [16. Segment Tree](#16-segment-tree)

---

## Repository Overview

- **Owner**: Mir-Ilham
- **Repository URL**: [https://github.com/Mir-Ilham/Data-Structures-and-Algorithms](https://github.com/Mir-Ilham/Data-Structures-and-Algorithms)
- **Branch**: `main`

The repository is organized into topic-specific directories. Many topics contain subdirectories for granular implementations, along with sample `input.txt` / `output.txt` files for easy testing.

---

## Programming Language

- **Primary Language**: C++ (100%)
- All code is written in modern C++ and can be compiled with any standard C++ compiler (g++, clang++, etc.).

---

## Goals & Scope

- Provide **correct and efficient** implementations of core DSA topics.
- Follow a logical learning progression (easy → advanced).
- Serve as a ready reference for competitive programming, interview preparation, and self-study.
- Keep implementations self-contained and easy to understand.

---

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/Mir-Ilham/Data-Structures-and-Algorithms.git
   cd Data-Structures-and-Algorithms
   ```

2. Navigate to any topic folder.

3. Compile and run a `.cpp` file:

   ```bash
   g++ -std=c++17 filename.cpp -o output
   ./output
   ```

4. Many folders include `input.txt` (test data) and `output.txt` (expected results) for quick verification.

## Contents

### 1. Pre-computation Techniques

Techniques to speed up queries using pre-calculated values.

- Prefix Sum
- Prefix Sum on 2D Array

### 2. Linked List

Singly and doubly linked list operations.

- Basic Structure & Operations
- Doubly Linked List

### 3. Stack and Queue

Basic linear data structures and their applications.

- Stack Implementation
- Queue Implementation
- Expression conversion (infix to postfix/prefix, etc.)

### 4. Sorting Techniques

Classic sorting algorithms with different time complexities.

- Bubble Sort
- Insertion Sort
- Selection Sort
- Merge Sort
- Quick Sort

### 5. Subset Generation

Techniques to generate all subsets of a set/array.

Various subset generation methods (organized in subdirectories)

### 6. Binary Search

Efficient searching on sorted arrays and its variants.

- Basic Binary Search
- Lower Bound
- Upper Bound

### 7. Binary Tree

Fundamental tree traversals and structure.

- Basic Structure & DFS Traversals (Pre-order, In-order, Post-order)
- BFS Traversal (Level-order)

### 8. Binary Search Tree

Self-balancing search tree operations.

- Insertion, deletion, search, and traversals.

### 9. Heap

Priority queue and heap-based algorithms.

- Heap Implementation
- Heapify
- Heap Sort

### 10. Policy-Based Data Structures

Advanced C++ STL extensions (GNU Policy-Based Data Structures).

- Ordered sets with order statistics
- `find_by_order`, `order_of_key`, etc.

### 11. Graph

Graph traversal, shortest paths, and connectivity algorithms.

- Disjoint Set (Union-Find)
- Minimum Spanning Tree
- Dijkstra Algo
- Bellman Ford
- Floyd Warshall Algorithm
- Strongly Connected Components (Kosaraju)

### 12. Trie

Prefix tree for efficient string operations.

- Trie Implementation
- Trie Problems / Implement Trie 2

### 13. Ternary Search

Divide-and-conquer search on unimodal functions.

- Ternary search implementation

### 14. Dynamic Programming

Classic DP problems categorized by state representation.

- 1D DP
- 2D DP
- `01` Knapsack
- Longest Common Subsequence
- Longest Increasing Subsequence
- Edit Distance
- Partition DP / Matrix Chain Multiplication

### 15. Sparse Table

Static range query data structure (`O(1)` queries after `O(n log n)` preprocessing).

- Implementation: Sparse Table for range minimum/maximum queries

### 16. Segment Tree

Advanced tree for range queries and updates.

- Implementation: Segment Tree (range sum/min/max queries, updates)
