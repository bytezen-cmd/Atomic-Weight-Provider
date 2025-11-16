# Atomic-Weight-Provider

This project provides a utility to calculate or retrieve atomic weights of elements. It's designed to be a simple, efficient, and easy-to-use tool for developers and scientists alike.

## Features

*   **Accurate Data**: Provides precise atomic weight values.
*   **Easy Integration**: Designed for straightforward integration into other C++ projects.
*   **Lightweight**: Minimal dependencies for efficient performance.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   A C++ compiler (e.g., MSVC, GCC, Clang)
*   Visual Studio (for Windows users, recommended for `.vcxproj` files)

### Building the Project

#### Using Visual Studio (Windows)

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/bytezen-cmd/Atomic-Weight-Provider.git
    cd Atomic-Weight-Provider
    ```
2.  **Open the solution**: Open `Atomic-Weight-Provider.sln` in Visual Studio.
3.  **Build**: Build the solution (`Build > Build Solution` or `Ctrl+Shift+B`).

#### Using GCC/Clang (Linux/macOS/WSL)

If you are not using Visual Studio, you might need to compile `Source.cpp` manually.

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/bytezen-cmd/Atomic-Weight-Provider.git
    cd Atomic-Weight-Provider
    ```
2.  **Compile**:
    ```bash
    g++ Source.cpp -o AtomicWeightProvider
    ```
    (Replace `g++` with `clang++` if you prefer Clang.)

### Running the Application

After building, you can run the executable from your build directory or the command line.

#### Windows (Visual Studio)

The executable will typically be found in `x64/Debug/` or `x64/Release/` within your project directory.

```bash
.\x64\Debug\Atomic-Weight-Provider.exe
```

#### Linux/macOS/WSL

```bash
./AtomicWeightProvider
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find a bug or have a feature request.

## License

This project is licensed under the terms of the `LICENSE.txt` file.
