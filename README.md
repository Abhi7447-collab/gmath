# gmath 📐

![gmath](https://img.shields.io/badge/gmath-Godot%20Inspired%20Math%20Library-blue.svg)

Welcome to **gmath**, a Godot-inspired math library designed for Ebintengine and other Go game engines. This library provides essential mathematical functions and utilities to enhance your game development experience.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Features

- **Easy to Use**: The library offers a simple API for common mathematical operations.
- **Performance**: Optimized for speed, ensuring smooth gameplay.
- **Compatibility**: Works seamlessly with Ebintengine and other Go-based game engines.
- **Inspired by Godot**: Leverages concepts from the Godot engine to provide familiar functionality.

## Installation

To install gmath, clone the repository and include it in your project. Use the following command:

```bash
git clone https://github.com/Abhi7447-collab/gmath.git
```

After cloning, navigate to the gmath directory and follow the instructions in the documentation.

## Usage

To use gmath in your project, import the library in your Go files. Here’s a basic example:

```go
import "github.com/Abhi7447-collab/gmath"

// Example usage of gmath functions
result := gmath.Add(5, 10)
fmt.Println(result) // Output: 15
```

For more detailed examples, check the documentation in the repository.

## Functions

gmath provides a variety of functions to assist in your game development:

### Basic Arithmetic

- `Add(a int, b int) int`: Returns the sum of two integers.
- `Subtract(a int, b int) int`: Returns the difference of two integers.
- `Multiply(a int, b int) int`: Returns the product of two integers.
- `Divide(a int, b int) (int, error)`: Returns the quotient of two integers. Handles division by zero.

### Geometry

- `Distance(x1, y1, x2, y2 float64) float64`: Calculates the distance between two points.
- `AreaOfCircle(radius float64) float64`: Computes the area of a circle given its radius.

### Trigonometry

- `Sin(angle float64) float64`: Returns the sine of the angle.
- `Cos(angle float64) float64`: Returns the cosine of the angle.
- `Tan(angle float64) float64`: Returns the tangent of the angle.

### Matrix Operations

- `MatrixMultiply(a [][]float64, b [][]float64) ([][]float64, error)`: Multiplies two matrices.
- `MatrixTranspose(matrix [][]float64) [][]float64`: Transposes a given matrix.

## Contributing

We welcome contributions to gmath! If you have ideas for new features or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push to your branch and create a pull request.

Your contributions help make gmath better for everyone.

## License

gmath is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, please reach out via the Issues section on GitHub or contact the repository owner directly.

## Releases

To download the latest release of gmath, visit [this link](https://github.com/Abhi7447-collab/gmath/releases). Follow the instructions to download and execute the latest version.

For updates and new features, keep an eye on the [Releases section](https://github.com/Abhi7447-collab/gmath/releases) of the repository.

---

Thank you for checking out gmath! We hope this library helps you create amazing games with ease. Happy coding!