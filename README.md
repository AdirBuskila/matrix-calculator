# Matrix Calculator

A command-line Matrix Calculator written in C/C++ (choose your preference).  
This project aims to provide a simple yet powerful tool for basic matrix operations and, in later versions, more advanced linear algebra features. 

---

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Roadmap](#roadmap)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact / Credits](#contact--credits)

---

## About

This project was built by a group of friends who wanted to:  
1. Practice writing clean, organized code in C/C++.  
2. Learn how to collaborate using GitHub.  
3. Implement core matrix operations from scratch.

Our goal is to provide a library and command-line tool that can handle basic matrix arithmetic, and evolve it into a robust utility for advanced linear algebra calculations.  

---

## Features

### Version 1.0 (Planned)
- **Matrix Addition**  
- **Matrix Subtraction**  
- **Matrix Multiplication**  
- **Matrix Transpose**  

### Future Versions
- **Matrix Inversion**  
- **Determinant Calculation**  
- **Solving Linear Equations (Ax = b)**  
- **Eigenvalues and Eigenvectors**  
- **LU Decomposition / Other Advanced Operations**  

---

## Roadmap

1. **Version 1.0**  
   - [ ] Implement basic operations (add, subtract, multiply).  
   - [ ] Write tests to confirm outputs are correct.  
   - [ ] Provide command-line input/output.  

2. **Version 2.0**  
   - [ ] Matrix inversion.  
   - [ ] Determinant calculation.  
   - [ ] Code refactoring & optimization.

3. **Version 3.0**  
   - [ ] Eigenvalues & eigenvectors.  
   - [ ] Further advanced operations or decomposition methods.

See our [GitHub Projects](./../../projects) or [Issues](./../../issues) for additional tasks and milestone details (if you are using them).

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/adirbuskila/matrix-calculator.git
   cd matrix-calculator
   ```

2. **Build**  
   Using a simple Makefile (example – adjust file names as needed):
   ```bash
   make
   ```
   This should produce an executable (e.g., `matrix_calculator`).

3. **Run**  
   ```bash
   ./matrix_calculator
   ```

For more advanced build systems, we may use CMake or another build tool in the future.

---

## Usage

Once compiled, run the command:
```bash
./matrix_calculator
```
You’ll be prompted to enter the dimensions of your matrices and then the matrix elements row by row. After that, you can choose the operation you want to perform.

A typical flow might look like:

1. **Enter the dimensions** (e.g., 2x2).  
2. **Enter each row** of the matrix.  
3. **Choose an operation** (e.g., add, subtract, multiply, transpose, etc.).  
4. **Enter second matrix** if required.  
5. **View the result** on the screen.

*(An example input/output demonstration can go here once your functionality is finalized.)*

---

## Contributing

We welcome all contributions! Please see our [CONTRIBUTING.md](./CONTRIBUTING.md) file (if you choose to create one) for details on our code style and branch/pull request workflow.  

Typical workflow:
1. **Fork** this repository (if you’re external).  
2. **Create a feature branch** off `main`: `git checkout -b feature/my-awesome-feature`.  
3. **Commit** your changes and push to your branch.  
4. Open a **Pull Request** on GitHub, describing your feature.  
5. Discuss and review until it’s ready to merge.

For internal collaborators, feel free to make feature branches within the same repo.

---

## License

This project is licensed under the [MIT License](./LICENSE). Feel free to use, distribute, and modify it. See the LICENSE file for more details.

---

## Contact / Credits

**Created by:**  
- [Friend #1](https://github.com/Friend1)  
- [Friend #2](https://github.com/Friend2)  
- [Friend #3](https://github.com/Friend3)  
- [You](https://github.com/YourUserName)

Feel free to open an [issue](./../../issues) or reach out if you have any questions or suggestions!

Happy Calculating!
