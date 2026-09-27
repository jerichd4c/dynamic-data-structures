<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/jerichd4c/dynamic-data-structures-cohen/tree/main/kingdom-binary-tree">
    <img src="https://raw.githubusercontent.com/jerichd4c/ReflexJDBC/main/cpp_logo.svg" alt="Logo" width="80" height="80">
  </a>
</div>


<div align="center">
  <h3 align="center">Kingdom Binary Tree 🏆</h3>

  <p align="center">
    <strong>Final Project</strong> — a C++ binary tree implementation for managing royal family succession lines
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#csv-file-format">CSV File Format</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## About The Project

Binary tree implementation for royal family genealogy and succession. Manages crown transfer rules, living heir tracking, and family member operations.

**`ArbolBinario.cpp`**: Main implementation containing:
- Binary tree structure for family members
- CSV file import/export functionality
- Royal succession line calculation with complex rules
- CRUD operations for family members
- King death and abdication handling

Features:
- Automatic king assignment when current king dies
- Succession line display (living members only)
- Family tree visualization
- Node modification (except id and father_id)
- Support for primogeniture and secondary heir rules
- Automatic crown transfer for kings over 70 years old

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![C++][Cpp-shield]][Cpp-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To get a local copy up and running, compile the source code natively via GCC/G++.

### Prerequisites

* GCC / G++ (MinGW on Windows)
* C++11 or higher

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jerichd4c/dynamic-data-structures-cohen.git
   ```
2. Navigate to the project directory
   ```sh
   cd dynamic-data-structures-cohen/kingdom-binary-tree
   ```
3. Compile the project:
   ```sh
   g++ src/ArbolBinario.cpp -o bin/ArbolBinario.exe
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

Execute the binary from the project root directory:

```sh
bin/ArbolBinario.exe
```

Note: Always run the program from the repository root to ensure CSV files are found correctly.

### Menu Options

1. **Display family tree** - Shows the complete genealogical tree
2. **Show succession line** - Displays current line of succession (living members only)
3. **Modify a node** - Update family member data (except id and father_id)
4. **Add family member** - Add new member to the family tree
5. **Kill the king** - Mark current king as dead (triggers automatic succession)
6. **Show current king** - Display the reigning monarch's information
7. **Exit** - Close the application

### Sample Data Files

Two CSV files are provided in the `data/` directory:
- `family_tree_ordered.csv` - Pre-sorted family data
- `family_tree_unordered.csv` - Random order for testing tree construction

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## CSV File Format

```
id;name;last_name;gender;age;id_father;is_dead;was_king;is_king
```

| Column | Description | Values |
|--------|-------------|--------|
| id | Unique identifier | Integer |
| name | First name | String |
| last_name | Last name | String |
| gender | Gender | H (Male) / M (Female) |
| age | Age | Integer |
| id_father | Father's ID | Integer (empty for root) |
| is_dead | Is deceased | 0 (No) / 1 (Yes) |
| was_king | Was previously king | 0 (No) / 1 (Yes) |
| is_king | Is current king | 0 (No) / 1 (Yes) |

Example entry:
```
1;Arthur;Royal;H;80;;0;1;1
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[Cpp-shield]: https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white
[Cpp-url]: https://isocpp.org/
