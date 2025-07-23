# Hello World and Calculator Program in C++

---

## Program 1: Hello World

**Aim:** To study the basic input/output structure and basic structure of a C++ code  
**Apparatus:** Programiz / VS Code

---

### Theory

The Hello World program demonstrates the use of the `cout` function. To enable this, the necessary header file `iostream` is included.

#### iostream

In C++, `iostream` is a header file in the Standard Library that provides input and output functionality. It includes:

- `cin`: for reading input (keyboard)
- `cout`: for displaying output (console)

#### #include (Preprocessor Directive)

`#include` is a preprocessor directive in C++. It tells the compiler to include the contents of another file (like `iostream`) before actual compilation. Preprocessor directives begin with `#` and are processed before the compilation phase.

#### cout

`cout` is an object of the `ostream` class. It is used with the insertion operator `<<` to print text, numbers, or other data to the console.

#### using namespace std

This statement allows you to use elements from the standard namespace (like `cout`, `cin`, etc.) without prefixing them with `std::`. The `std` namespace includes all standard functions and classes from the C++ library.

---

## Program 2: Calculator Program

**Aim:** To study the basic `cin` / `cout` usage and basic mathematical operations  
**Apparatus:** Programiz / VS Code

---

### Algorithm

1. Initialize two variables `a` and `b`  
2. Variables can be of `int`, `float`, etc.  
3. Take input from the user using `cin`  
4. Perform operations:  
   - `+` for addition  
   - `-` for subtraction  
   - `*` for multiplication  
   - `/` for division  
5. Store each result in a separate variable  
6. Output results using `cout`

---

### Theory

#### cin

`cin` is an object of the `istream` class (from the `iostream` header). It is used with the extraction operator `>>` to get input from the user through the keyboard.

#### endl

`endl` is a manipulator that inserts a newline character (`\n`) into the output stream and flushes the buffer. It ensures the output is displayed immediately.

---

## Conclusion

Through the Hello World and Calculator programs, we learn the foundational elements of C++:

- How to use `#include`, `cout`, `cin`, and `endl`
- How to initialize and use variables
- How to perform basic input/output operations
- The importance of preprocessor directives and namespaces

These concepts form the base for writing more complex C++ programs.
