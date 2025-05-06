<!-- Badges -->

[![.NET](https://img.shields.io/badge/.NET-6.0-blue)](https://dotnet.microsoft.com/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

# Linear Algebra Solver – Windows Forms C#

**Project Description**  
A Windows Forms application built in C# (Visual Studio) to solve linear algebra problems:

- Gaussian Elimination
- Gauss–Jordan Elimination
- Matrix Inverse calculation

---

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation & Usage](#installation--usage)
- [Screenshots](#screenshots)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- Simple and intuitive GUI
- Algorithm selection from a dropdown
- Optional step-by-step solution display
- Support for up to 10×10 matrices

---

## Prerequisites

- [.NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/6.0) or later
- Visual Studio 2022 (or any version supporting Windows Forms)
- Windows 10 or later

---

## Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/AMR-MOHAMED0/MyLinearAlgebraSolver.git
   cd MyLinearAlgebraSolver
   ```
2. **Open in Visual Studio**  
   Open `SolverApp.csproj`
3. **Build and run**
   - Press **F5** in Visual Studio
   - Or via CLI:
     ```bash
     dotnet build
     dotnet run --project SolverApp.csproj
     ```

---

## Screenshots

![Gaussian Elimination](Resources/screenshots/gaussian.png)  
_Gaussian Elimination window_

![Gauss-Jordan](Resources/screenshots/jordan.png)  
_Gauss-Jordan Elimination window_

![Matrix Inverse](Resources/screenshots/inverse.png)  
_Matrix Inverse calculation window_

![Enter Size of Matrix](Resources/screenshots/Enter_Size_of_Matrix.png)  
_Enter Size of Matrix window_

![Enter Augmented Matrix](Resources/screenshots/Enter_Augmented_Matrix.png)  
_Enter Augmented Matrix window_

![Solve Matrix](Resources/screenshots/Solve_Matrix.png)  
_Solve Matrix window_

![Result](Resources/screenshots/Result.png)  
_Result window_

---

## Code Structure

```
MyLinearAlgebraSolver/
├── .gitignore
├── LICENSE
├── README.md
├── SolverApp.csproj
├── Program.cs
├── MainForm.cs
├── MainForm.Designer.cs
├── GaussianElimination.cs
├── JordanElimination.cs
├── MatrixInverse.cs
└── Resources/
    └── screenshots/
        ├── gaussian.png
        ├── jordan.png
        └── inverse.png
```

---

## Contributing

1. Fork this repository
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

- GitHub: [AMR-MOHAMED0](https://github.com/AMR-MOHAMED0)
- LinkedIn: [Amr Mohamed](https://www.linkedin.com/in/amr-mohamed-88586b294/)

```

```
