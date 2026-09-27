<a id="readme-top"></a>

<br />
<div align="center">
  <img src="https://img.shields.io/badge/Dynamic%20Data%20Structures-URU-blue?style=for-the-badge" alt="Dynamic Data Structures" width="380" height="40">

<h3 align="center">Dynamic Data Structures - Sebastian Cohen</h3>

  <p align="center">
    Repository for the Dynamic Data Structures course at URU. It gathers the final versions of the class assignments, from linked lists to trees and graphs.
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-repository">About The Repository</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#repository-structure">Repository Structure</a></li>
    <li><a href="#main-projects">Main Projects</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>

## About The Repository

This repository brings together the material covered in the **Dynamic Data Structures** course. Its purpose is to keep the final, working version of each assignment in one organized place — linked lists, stacks and queues, binary trees, and graphs, all implemented from scratch in C++.

Each project folder is self-contained and has its own README with setup instructions and implementation details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![C++][Cpp-badge]][Cpp-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

Each project has its own compile/run instructions — see its individual README linked in [Main Projects](#main-projects).

### Prerequisites

* GCC / G++ (MinGW on Windows, or the standard package on Linux/macOS)
* C++11 or higher

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jerichd4c/dynamic-data-structures-cohen.git
   ```
2. Open the folder for the project you want to run.
3. Follow that project's own README to compile and run it.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Repository Structure

These are the assignments currently available in the repository:

* `circular-linked-list-assignment/`: simple and doubly circular linked lists for managing person data, with file persistence.
* `stack-queue-assignment/`: stack inversion, priority queue processing, and a linked-list-based priority queue.
* `binary-tree-demo/`: an N-ary genealogy tree and a self-balancing AVL tree.
* `graph-tree-assignment/`: graph traversal via adjacency lists and adjacency matrices.
* `kingdom-binary-tree/`: **final project** — a binary tree modeling royal family succession, with automatic crown transfer rules.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Main Projects

These are the assignments developed during the course. Each one has its own internal documentation.

### [Kingdom Binary Tree](kingdom-binary-tree/README.md) 🏆 Final Project
A binary tree implementation for royal family genealogy and succession — automatic king assignment on death, primogeniture and secondary heir rules, and automatic crown transfer for kings over 70.
* **Features**: CSV import/export, living-heirs succession line, full CRUD on family members.
* **Documentation**: [Project README](kingdom-binary-tree/README.md)

### [Circular Linked List Assignment](circular-linked-list-assignment/README.md)
Simple and doubly circular linked list implementations for managing person records.
* **Features**: insert at position, delete by name, search by ID, forward/reverse display, CSV file persistence.
* **Documentation**: [Project README](circular-linked-list-assignment/README.md)

### [Stack & Queue Assignment](stack-queue-assignment/README.md)
Three independent programs built around fundamental linear data structures.
* **Features**: in-place stack inversion, FIFO-compliant queue processing, and a priority queue built on linked lists.
* **Documentation**: [Project README](stack-queue-assignment/README.md)

### [Binary Tree Demo](binary-tree-demo/README.md)
Two specialized tree structures: an interactive genealogy tree and a self-balancing AVL tree.
* **Features**: CSV-driven genealogy tree construction, logarithmic-time AVL operations.
* **Documentation**: [Project README](binary-tree-demo/README.md)

### [Graph Tree Assignment](graph-tree-assignment/README.md)
Two graph representations built to compare their trade-offs directly.
* **Features**: adjacency list (sparse) and adjacency matrix (dense) implementations of the same graph operations.
* **Documentation**: [Project README](graph-tree-assignment/README.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

This roadmap summarizes the course progress and can keep growing as new units or assignments are added.

- [x] Circular linked lists (simple and doubly linked).
- [x] Stacks and queues, including a priority queue.
- [x] Binary trees: a genealogy tree and a self-balancing AVL tree.
- [x] Graphs: adjacency list and adjacency matrix representations.
- [x] Final project: a binary tree modeling royal succession rules.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[Cpp-badge]: https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white
[Cpp-url]: https://isocpp.org/
