# Hello World

This is a simple "Hello, World!" program in C++ to demonstrate a basic project setup and build process.

## Prerequisites

To compile and run this project, you will need a C++ compiler installed on your system. A common compiler is g++.

*   **Windows**: You can install a compiler via [MinGW-w64](https://www.mingw-w64.org/) or by installing Visual Studio with the "Desktop development with C++" workload.
*   **macOS**: You can install Command Line Tools for Xcode which includes the Clang compiler.
*   **Linux**: You can install the build-essential package which includes g++.
    ```bash
    sudo apt-get update
    sudo apt-get install build-essential
    ```

## Building the Project

You can compile the `HelloWorld.cpp` file using your C++ compiler.

```bash
# Using g++
g++ main.cpp -o helloworld
```

## Running the Program

Once compiled, you can run the executable.

```bash
# On Windows
.\helloworld.exe

# On macOS or Linux
./helloworld
```

## The Code

Here is the code.

```cpp
//basic hello world in C++

#include <iostream>
#include "Main.h"

void printHelloWorld() {
	std::cout << "Hello World!" << std::endl;
}

int main() {
	printHelloWorld();
	return 0;
}
```