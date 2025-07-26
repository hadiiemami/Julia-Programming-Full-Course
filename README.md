# Julia Programming Tutorials

![Julia Logo](https://julialang.org/assets/infra/logo.svg)

A comprehensive collection of Jupyter Notebooks covering essential and advanced topics in the Julia programming language. This repository is designed for beginners and intermediate learners aiming to master Julia for data science, scientific computing, and general programming.

## Overview
This repository contains Jupyter Notebooks that explore key concepts and techniques in Julia. Each notebook focuses on a specific topic, providing clear explanations, code examples, and practical applications. The tutorials are ideal for students, researchers, and developers interested in leveraging Julia's high-performance capabilities.

## Table of Contents
- [Tutorials](#tutorials)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Tutorials
The repository includes the following Jupyter Notebooks, each covering a distinct topic in Julia programming:

1. **1 - TXT File.ipynb**: Reading and writing text files in Julia.
2. **2 - CSV Files.ipynb**: Handling CSV files for data import and export.
3. **3 - Image.ipynb**: Processing and manipulating images using Julia.
4. **4 - Json File.ipynb**: Working with JSON files for structured data.
5. **5 - XLSX File.ipynb**: Managing Excel files (XLSX) for data analysis.
6. **Arrays.ipynb**: Exploring arrays, Julia’s core data structure.
7. **Classification.ipynb**: Implementing classification algorithms in Julia.
8. **Dictionarys.ipynb**: Using dictionaries for key-value data storage.
9. **Error Handling.ipynb**: Managing errors and exceptions in Julia.
10. **Error Types.ipynb**: Understanding different error types and their handling.
11. **Functions.ipynb**: Defining and using functions for modular programming.
12. **Loops.ipynb**: Implementing loops (for, while) for iterative tasks.
13. **Matrix.ipynb**: Working with matrices for numerical computations.
14. **Operators and Conditional Statements in Julia.ipynb**: Using operators and conditionals for logic control.
15. **Plot and Visualization.ipynb**: Creating visualizations using Julia’s plotting libraries.
16. **Sets.ipynb**: Handling sets for unique data collections.
17. **Variables and Data Types in Julia.ipynb**: Understanding Julia’s variables and data types.

## Prerequisites
- **Julia**: Version 1.6 or higher (recommended).
- **Jupyter Notebook**: For running `.ipynb` files.
- **Required Julia Packages**:
  - `CSV.jl` for CSV file handling
  - `DataFrames.jl` for data manipulation
  - `JSON.jl` for JSON file processing
  - `XLSX.jl` for Excel file operations
  - `Images.jl` for image processing
  - `Plots.jl` for visualizations
  - `MLJ.jl` for classification tasks
  (See `requirements.txt` for a detailed list.)

## Installation
1. **Install Julia**:
   - Download and install Julia from [julialang.org](https://julialang.org/downloads/).
   - Follow the setup instructions for your operating system.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/julia-tutorials.git
   ```

3. **Set Up Jupyter Notebook**:
   - Install Jupyter via Julia:
     ```julia
     using Pkg
     Pkg.add("IJulia")
     ```
   - Launch Jupyter:
     ```julia
     using IJulia
     notebook()
     ```

4. **Install Required Packages**:
   - Install dependencies listed in `requirements.txt`:
     ```bash
     julia -e 'using Pkg; Pkg.add(readlines("requirements.txt"))'
     ```
   - Alternatively, install packages manually in Julia:
     ```julia
     Pkg.add(["CSV", "DataFrames", "JSON", "XLSX", "Images", "Plots", "MLJ"])
     ```

## Usage
1. Navigate to the repository folder:
   ```bash
   cd julia-tutorials
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open and run any `.ipynb` file to explore the tutorials.
4. Follow the code examples and comments in each notebook for hands-on learning.

## Example
To work with CSV files:
- Open `2 - CSV Files.ipynb`.
- Run the cells to read, manipulate, and save CSV data using `CSV.jl` and `DataFrames.jl`.

## Notes
- Each notebook is self-contained with explanations and examples.
- Ensure you have sufficient memory for image processing and visualization tasks.
- For classification tasks, `MLJ.jl` requires additional setup; refer to the notebook for details.
- Check the Julia documentation for advanced usage of packages.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Add or improve notebooks with clear comments and examples.
4. Submit a pull request with a description of changes.

## License
MIT License