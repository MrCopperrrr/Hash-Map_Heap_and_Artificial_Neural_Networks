# Data_Structures_and_Algorithms_Assignment_2

This assignment focuses on implementing and utilizing Hash-Map and Heap data structures to enhance the development of Artificial Neural Networks.

## 1. Introduction

This assignment is divided into two main tasks: implementing the HashMap and Heap data structures (Task 1), and using these data structures to develop a multi-layer feedforward neural network (Task 2).


## 2. Task 1: Hash Table and Heap Implementation

### 2.1. HashMap (xMap)

*   Implement the `IMap` interface and the concrete `xMap` class in `./include/hash/xMap.h`.
*   Implement the necessary methods including `put`, `get`, `remove`, `containsKey`, etc.
*   Ensure proper collision handling using doubly linked lists.

### 2.2. Heap

*   Implement the `IHeap` interface and the concrete `Heap` class in `./include/heap/Heap.h`.
*   Implement methods like `push`, `pop`, `peek`, `remove`, `contains`, etc.
*   Support building a heap from an array (`heapify`).

## 3. Task 2: Multi-Layer Perceptron (MLP)

*   Implement the neural network layers, loss functions, metrics, models, and optimizers within the `./include/ann` and `./src/ann` directories.
*   Refer to the "Artificial Neural Networks" guide for implementation details.
*   Implement the classes in the suggested order: layers, loss functions, metrics, models, optimizers.

## 4. Compilation

*   Use the provided `Makefile` (run `make` in the terminal) or the `compilation-command.sh` script.
*   Alternatively, use an IDE (e.g., NetBeans, VSCode) and configure it to compile with C++17 support.

## 5. Important Notes

*   Complete Task 1 *before* starting Task 2.
*   Task 2 relies on the `DLinkedList` from Assignment 1, and needs the Backward-Iterator of `DLinkedList`. You have to add the Backward-Iterator to `DLinkedList`
*   Ensure your code adheres to the specified interfaces and implementation guidelines.
