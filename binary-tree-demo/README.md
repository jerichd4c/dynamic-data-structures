<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/jerichd4c/dynamic-data-structures/tree/main/binary-tree-demo">
    <img src="https://raw.githubusercontent.com/jerichd4c/ReflexJDBC/main/cpp_logo.svg" alt="Logo" width="80" height="80">
  </a>
</div>


<div align="center">
  <h3 align="center">Binary Tree Demo</h3>

  <p align="center">
    A comprehensive C++ project implementing advanced data structures including Genealogy Trees and AVL Trees.
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
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
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

This project contains optimized C++ implementations of specialized data structures:
- **`ArboGenealogico.cpp`**: Parses structured `.csv` data to construct, query, and modify an interactive N-ary Genealogy Tree.
- **`ArbolAvl.cpp`**: Implements a self-balancing binary search tree (AVL) for continuous logarithmic time complexity operations.

### Built With

* [![C++][Cpp-shield]][Cpp-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To get a local copy up and running, follow these simple steps to compile the source code natively via GCC/G++.

### Prerequisites

* GCC / G++ compiler (MinGW on Windows, or standard packages natively on Linux/macOS)
* Support for C++11 or higher

### Installation & Compilation

1. Clone the repo
   ```sh
   git clone https://github.com/jerichd4c/dynamic-data-structures.git
   ```
2. Navigate to the project directory
   ```sh
   cd dynamic-data-structures/binary-tree-demo
   ```
3. Compile the desired data structure into the `bin/` folder
   ```sh
   # Compile Genealogy Tree
   g++ src/ArboGenealogico.cpp -o bin/ArboGenealogico.exe
   
   # Compile AVL Tree
   g++ src/ArbolAvl.cpp -o bin/ArbolAvl.exe
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [ ] Implement a proper tree data structure for the genealogy tree.
- [ ] Refactor the first tree implementation to use recursive methods.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

Execute the compiled binaries directly from the workspace root (this ensures relative data files, like `arbolGenealogico.csv` located inside `bin/`, load correctly):

```sh
# Run Genealogy Tree
./bin/ArboGenealogico.exe

# Run AVL Tree
./bin/ArbolAvl.exe
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Cpp-shield]: https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white
[Cpp-url]: https://isocpp.org/
