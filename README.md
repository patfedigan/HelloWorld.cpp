# HelloWorld.cpp

A simple C++ program that prints "Hello, World!" to the console.

## Description

This is a basic C++ implementation of the traditional "Hello World" program. It demonstrates the fundamental structure of a C++ application and serves as a starting point for learning the language.

## Getting Started

### Prerequisites

- C++ compiler (g++, clang, MSVC, etc.)

### Compilation

```bash
# Using g++
g++ -o hello HelloWorld.cpp

# Using clang
clang++ -o hello HelloWorld.cpp
```

### Running the Program

```bash
./hello
```

Expected output:
```
Hello, World!
```

## File Structure

- `HelloWorld.cpp` - Contains the main C++ source code

## Code

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

## License

MIT
