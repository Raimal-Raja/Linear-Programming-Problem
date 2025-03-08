# Linear Programming Problem

This repository provides an in-depth exploration of linear programming (LP) problems, including their formulation, solution methods, and practical applications. The content is structured to guide users from fundamental concepts to advanced implementations, leveraging state-of-the-art optimization tools.

## Table of Contents

- [Introduction](#introduction)
- [Linear Programming Fundamentals](#linear-programming-fundamentals)
- [Optimization Tools and Solvers](#optimization-tools-and-solvers)
  - [OR-Tools](#or-tools)
  - [HiGHS Optimization Solver](#highs-optimization-solver)
  - [GLOP](#glop)
- [Project Structure](#project-structure)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Resources and Further Reading](#resources-and-further-reading)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Linear programming is a method to achieve the best outcome in a mathematical model whose requirements are represented by linear relationships. It is widely used in various fields such as economics, engineering, military, and transportation for optimizing processes and resource allocation.

## Linear Programming Fundamentals

A standard linear programming problem aims to maximize or minimize a linear objective function subject to a set of linear constraints. The general form is:

```
Maximize (or Minimize): c₁x₁ + c₂x₂ + ... + cₙxₙ

Subject to:
a₁₁x₁ + a₁₂x₂ + ... + a₁ₙxₙ ≤ b₁
a₂₁x₁ + a₂₂x₂ + ... + a₂ₙxₙ ≤ b₂
...
aₘ₁x₁ + aₘ₂x₂ + ... + aₘₙxₙ ≤ bₘ

and x₁, x₂, ..., xₙ ≥ 0
```

Where:
- `c₁, c₂, ..., cₙ` are coefficients of the objective function.
- `aᵢⱼ` are coefficients of the constraints.
- `b₁, b₂, ..., bₘ` are the right-hand side constants of the constraints.
- `x₁, x₂, ..., xₙ` are the decision variables.

For a comprehensive overview, refer to the [Linear Programming Wikipedia page](https://en.wikipedia.org/wiki/Linear_programming).

## Optimization Tools and Solvers

This project utilizes several advanced optimization tools and solvers:

### OR-Tools

Developed by Google's Operations Research Team, OR-Tools is an open-source software suite for optimization, including linear programming, mixed-integer programming, and constraint programming. It supports multiple programming languages such as C++, Java, .NET, and Python. More information can be found on the [OR-Tools Wikipedia page](https://en.wikipedia.org/wiki/OR-Tools) and the official [OR-Tools GitHub repository](https://github.com/google/or-tools).

### HiGHS Optimization Solver

HiGHS is an open-source optimization solver for linear programming (LP), mixed-integer programming (MIP), and quadratic programming (QP) problems. Written in C++, it provides interfaces to several programming languages, including Python and Julia. Detailed information is available on the [HiGHS Wikipedia page](https://en.wikipedia.org/wiki/HiGHS_optimization_solver) and the [HiGHS GitHub repository](https://github.com/ERGO-Code/HiGHS).

### GLOP

GLOP (Google Linear Optimization Package) is Google's open-source linear programming solver, created by the Operations Research Team. It is part of the OR-Tools suite and is designed to solve large-scale linear programming problems efficiently. For more details, visit the [GLOP Wikipedia page](https://en.wikipedia.org/wiki/GLOP) and the [GLOP source code](https://github.com/google/or-tools/tree/stable/ortools/glop).

## Project Structure

- `examples/`: Contains example LP problems and their solutions.
- `docs/`: Documentation and tutorials on linear programming concepts and solver usage.
- `src/`: Source code for implementing and solving LP problems using various solvers.
- `tests/`: Unit tests for validating the correctness of implementations.

## Installation and Setup

To set up the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Raimal-Raja/Linear-Programming-Problem.git
   cd Linear-Programming-Problem
   ```

2. **Install dependencies:**

   - For Python:

     ```bash
     pip install -r requirements.txt
     ```

   - For other languages, refer to the respective solver documentation in the `docs/` directory.

3. **Set up solvers:**

   - **OR-Tools:** Follow the [installation guide](https://developers.google.com/optimization/install) provided by Google.
   - **HiGHS:** Instructions are available on the [HiGHS GitHub repository](https://github.com/ERGO-Code/HiGHS).
   - **GLOP:** Included within the OR-Tools suite; no separate installation is required.

## Usage

Detailed usage instructions and examples are provided in the `examples/` and `docs/` directories. Users can explore various LP problems and learn how to implement and solve them using the aforementioned solvers.

## Resources and Further Reading

- [Linear Programming - Wikipedia](https://en.wikipedia.org/wiki/Linear_programming)
- [OR-Tools Documentation](https://developers.google.com/optimization)
- [HiGHS Documentation](https://highs.dev/)
- [GLOP Overview](https://developers.google.com/optimization/lp/glop)

## Contributing

Contributions are welcome! Please refer to the `CONTRIBUTING.md` file for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
