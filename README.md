# Compiler Construction Lab - Fall 2024

## University Details
- **University**: University Of Engineering & Technology, Lahore
- **Department**: Department of Computer Science
- **Course Code**: CS-471L
- **Course Title**: Compiler Construction Lab

## Instructor Details
- **Instructor Name**: Mr. Laeeq Khan Niazi

## Project Description
This repository contains a compiler developed during the Compiler Construction Lab course for the Fall 2024 semester. The project demonstrates the various stages of compiler design, including:

- **Lexical Analysis**: Tokenizing source code into meaningful symbols
- **Syntax Analysis**: Parsing tokens to create a syntactic structure (parse tree)
- **Semantic Analysis**: Checking for semantic errors and ensuring proper variable declarations, types, etc.
- **Intermediate Code Generation**: Producing an intermediate representation of the code
- **Code Optimization**: Enhancing the intermediate code for efficiency
- **Code Generation**: Generating the final machine code or executable


## Usage

To run your project on a new environment by setting up `g++`, cloning the repository, and executing your code using `code.txt`, here's a step-by-step guide.

### 1. **Install MinGW and Set Up `g++` Compiler on Windows**
MinGW provides `g++` for compiling C++ code on Windows.

#### Steps:
- **Download and Install MinGW**:
  1. Visit [MinGW's official site](https://sourceforge.net/projects/mingw/).
  2. Download the installer (e.g., `mingw-get-setup.exe`).
  3. Run the installer and choose the options to install `g++` (C++ compiler).

- **Set Environment Variables**:
  1. After installation, open the **System Properties** by right-clicking on **This PC** > **Properties** > **Advanced system settings** > **Environment Variables**.
  2. Under **System Variables**, select `Path` and click **Edit**.
  3. Add the path to the MinGW `bin` folder (e.g., `C:\MinGW\bin`) and click **OK**.

- **Verify Installation**:
  Open **Command Prompt** and run:
  ```bash
  g++ --version
  ```
  You should see the `g++` version printed.

### 2. **Clone the Repository**

If your code is hosted in a Git repository, follow these steps:

#### Steps:
1. **Install Git** (if not already installed):
   - Download Git from [git-scm.com](https://git-scm.com/), install it, and follow the prompts.

2. **Clone the Repository**:
   - Open **Command Prompt** or **Terminal** and run:
     ```bash
     git clone https://github.com/affan-ch/Compiler-Construction-Lab/
     ```


3. **Navigate to the Project Folder**:
   After cloning, move to the directory where your project is located:
   ```bash
   cd Compiler-Construction-Lab
   ```

### 3. **Compile and Run the Code**

Once you're inside the project directory:

#### Steps:
1. **Compile the `parser.cpp`**:
   ```bash
   g++ -std=c++11 parser.cpp -o parser
   ```

   This will compile `parser.cpp` using the C++11 standard and create an executable named `parser`.

2. **Run the Program**:
   Assuming your code reads input from a file (like `code.txt`), you can run it as:
   ```bash
   ./parser code.txt
   ```

   Ensure that `code.txt` exists in the same directory as your executable or provide the full path to `code.txt`.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.