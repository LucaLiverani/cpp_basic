# C++ Example Project

This project demonstrates how to compile and run C++ code on Windows.

## Prerequisites

- Windows operating system
- A C++ compiler (e.g., MinGW, Visual Studio)
- A text editor or IDE (e.g., Visual Studio Code, CLion)

## Setup

### Using MinGW

1. Download and install MinGW from [MinGW official website](https://www.mingw-w64.org/).
2. Uzip the folder and place it in C:/
3. Add the `bin` directory of MinGW to your system's PATH environment variable.
4. check that you can execute g++ commands using the following command:
    ```
    g++ --version
    ```

## Compiling and Running the Code

### Using MinGW

1. Open a command prompt.
2. Navigate to the directory containing your C++ source file.
3. Compile the code using the following command:
    ```
    g++ filename.cpp -o filename
    ```
4. check if filename.exe has been created using the command:
    ```
    dir
    ```
5. Run the compiled program:
    ```
    ./filename.exe
    ```

## Run the Code with an IDE

For simple development purpose you can run the code using Dev-C++ from (https://www.bloodshed.net/)
