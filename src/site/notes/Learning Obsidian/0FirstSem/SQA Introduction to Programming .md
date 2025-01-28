---
{"dg-publish":true,"permalink":"/learning-obsidian/0-first-sem/sqa-introduction-to-programming/","created":"2025-01-27T22:54:10.609+05:30","updated":"2025-01-28T18:52:16.533+05:30"}
---


/pub


1. **What is a programming language?**  
   A programming language is a formal set of rules and vocabulary used to write instructions that a computer can understand and execute. Examples include Python, Java, and C++.  

2. **What is syntax?**  
   Syntax refers to the set of rules that define how code must be structured and written in a programming language. For example, forgetting a semicolon in C++ is a syntax error.  

3. **What is a compiler?**  
   A compiler is a program that translates code written in a high-level programming language (like C++ or Java) into machine code (binary) that the computer can run directly.  

4. **What is an interpreter?**  
   An interpreter executes code line by line, translating and running it immediately (e.g., Python). Unlike a compiler, it does not create a standalone executable file.  

5. **What is a variable?**  
   A variable is a named container in a program that stores data (e.g., numbers, text) which can be modified or reused during execution.  

6. **What is a data type?**  
   A data type defines the kind of value a variable can hold, such as integers (`int`), decimals (`float`), text (`string`), or true/false (`boolean`).  

7. **What is a constant?**  
   A constant is a fixed value that cannot be changed during program execution. For example, `PI = 3.14` remains constant throughout the program.  

8. **What is an operator?**  
   An operator performs actions on values or variables, such as arithmetic (`+`, `-`), comparison (`==`, `>`), or logical operators (`AND`, `OR`).  

9. **What is an expression?**  
   An expression is a combination of variables, operators, and values that produces a result. For example, `5 + 3 * 2` evaluates to 11.  

10. **What is a statement?**  
    A statement is a complete instruction in a program that performs an action, like assigning a value (`x = 10`) or calling a function.  

11. **What is a function?**  
    A function is a reusable block of code that performs a specific task. For example, a `calculateSum()` function might add two numbers.  

12. **What is a parameter?**  
    A parameter is a variable listed in a function’s definition that receives data when the function is called. For example, `def greet(name):` has `name` as a parameter.  

13. **What is a return value?**  
    A return value is the result a function sends back after it completes its task. For example, a `square(4)` function might return `16`.  

14. **What is a loop?**  
    A loop repeats a block of code multiple times until a condition is met. Examples include `for` loops (fixed iterations) and `while` loops (condition-based).  

15. **What is a conditional statement?**  
    A conditional statement runs different code blocks based on whether a condition is true or false. For example: `if (age >= 18) { ... } else { ... }`.  

16. **What is an array?**  
    An array is a collection of items stored in contiguous memory locations. For example, `numbers = [1, 2, 3]` stores three integers.  

17. **What is a string?**  
    A string is a sequence of characters (text) enclosed in quotes. For example, `name = "Alice"` is a string variable.  

18. **What is a pointer?**  
    A pointer is a variable that stores the memory address of another variable. It is used for direct memory manipulation, common in languages like C/C++.  

19. **What is object-oriented programming (OOP)?**  
    OOP is a programming paradigm that organizes code into reusable "objects" containing data (attributes) and behaviors (methods).  

20. **What is a class?**  
    A class is a blueprint for creating objects in OOP. For example, a `Car` class might define attributes like `color` and methods like `drive()`.  

21. **What is an object?**  
    An object is an instance of a class. For example, `myCar = Car("red")` creates an object from the `Car` class with the color "red".  

22. **What is inheritance?**  
    Inheritance allows a class (child) to inherit properties and methods from another class (parent). For example, a `Dog` class can inherit from an `Animal` class.  

23. **What is encapsulation?**  
    Encapsulation is the practice of bundling data and methods within a class and restricting direct access to internal details for security and simplicity.  

24. **What is polymorphism?**  
    Polymorphism lets objects of different classes be treated as objects of a common superclass. For example, a `Circle` and `Square` can both have a `draw()` method.  

25. **What is abstraction?**  
    Abstraction simplifies complex systems by hiding unnecessary details and exposing only essential features. For example, a user interacts with a car’s steering wheel but not its engine mechanics.  

26. **What is debugging?**  
    Debugging is the process of identifying and fixing errors (bugs) in code to ensure the program works as intended.  

27. **What is an Integrated Development Environment (IDE)?**  
    An IDE is a software tool that combines code editing, debugging, and compiling features into one interface. Examples include Visual Studio Code and PyCharm.  

28. **What is pseudocode?**  
    Pseudocode is a plain-language outline of a program’s logic, written to plan algorithms before coding. It uses simple syntax like "IF temperature > 30 THEN print 'Hot'".  

29. **What is an algorithm?**  
    An algorithm is a step-by-step procedure to solve a problem. For example, a recipe to bake a cake is an algorithm.  

30. **What is a comment?**  
    A comment is a note in code that explains its purpose. It is ignored by the compiler/interpreter. For example: `// This function calculates the sum`.  

--- 




### **Types of Programming Languages**  
1. **How are programming languages categorized into *low-level* and *high-level*?**  
   Low-level languages (e.g., machine code, assembly) interact directly with hardware and are difficult for humans to read. High-level languages (e.g., Python, Java) use human-readable syntax and require translation (compilation/interpretation) to run.  

2. **What is *machine language*, and why is it considered the lowest level?**  
   Machine language consists of binary code (0s and 1s) that a computer’s CPU executes directly. It is hardware-specific and not human-friendly.  

3. **What is an *assembly language*?**  
   Assembly language uses symbolic codes (e.g., `MOV`, `ADD`) to represent machine instructions. It is slightly more readable than machine code but still requires an assembler to translate it.  

4. **Why are high-level languages preferred for modern programming?**  
   High-level languages are easier to write, read, and debug due to English-like syntax. They also abstract hardware details, making code portable across devices.  

5. **What is the difference between a *compiled* and an *interpreted* language?**  
   Compiled languages (e.g., C++) are translated entirely into machine code before execution. Interpreted languages (e.g., Python) are translated line by line at runtime.  

6. **Name examples of *high-level programming languages* and their common uses.**  
   - **Python**: Data science, web development.  
   - **Java**: Enterprise applications, Android apps.  
   - **JavaScript**: Web development (client-side scripting).  

---

### **Language Paradigms**  
7. **What is a *programming paradigm*?**  
   A paradigm is a style or approach to programming. Examples include procedural (step-by-step instructions), object-oriented (objects and classes), and functional (mathematical functions).  

8. **How does *procedural programming* differ from *object-oriented programming (OOP)*?**  
   Procedural programming focuses on functions and procedures, while OOP organizes code into reusable objects with data and methods.  

9. **What is a *scripting language*?**  
   Scripting languages (e.g., Python, JavaScript) automate tasks or control software applications. They are often interpreted and used for quick prototyping.  

---

### **Language Features & Design**  
10. **What is *portability* in programming languages?**  
    Portability refers to a program’s ability to run on different systems with minimal changes. High-level languages are more portable than low-level ones.  

11. **Why is *syntax* important in a programming language?**  
    Syntax defines the rules for writing valid code. Incorrect syntax (e.g., missing brackets) prevents the program from running.  

12. **What does *semantics* mean in programming?**  
    Semantics refers to the *meaning* of code. Even if syntax is correct, logical errors (incorrect semantics) can cause unintended behavior.  

13. **What is *memory management* in programming?**  
    Memory management involves allocating and deallocating memory during program execution. Low-level languages (e.g., C) require manual management, while high-level languages (e.g., Java) automate it.  

---

### **Language Translation & Execution**  
14. **What role does a *compiler* play in high-level languages?**  
    A compiler translates the entire high-level code into machine code before execution, producing an executable file (e.g., `.exe`).  

15. **How does an *interpreter* work differently from a compiler?**  
    An interpreter translates and executes code line by line, stopping at errors immediately. This allows for faster debugging but slower execution.  

16. **What is a *hybrid language*?**  
    Hybrid languages (e.g., Java) combine compilation and interpretation. Java code is compiled into bytecode, which is then interpreted by the JVM (Java Virtual Machine).  

---

### **Language Selection & Purpose**  
17. **Why might a programmer choose C over Python?**  
   C offers direct hardware control and faster execution for system-level programming (e.g., operating systems). Python prioritizes readability and ease of use for general-purpose tasks.  

18. **What is a *domain-specific language (DSL)*?**  
    A DSL is tailored for a specific task (e.g., SQL for databases, HTML for web pages). It is less versatile but highly efficient in its domain.  

---
Here’s a **categorized set of questions** focused on **compilers, interpreters, and related tools**, designed for revision and clarity:  

---

### **1. Language Translation Tools**  
1. **What is a compiler?**  
   A compiler translates *entire source code* (e.g., C++, Java) into machine-readable code (executable file) before execution.  

2. **What is an interpreter?**  
   An interpreter translates and executes code *line by line* (e.g., Python, JavaScript) without creating a standalone executable.  

3. **What is an assembler?**  
   An assembler converts *assembly language* (human-readable low-level code) into machine code.  

4. **What is the difference between a compiler and an interpreter?**  
   A compiler translates all code at once, while an interpreter translates and runs code line by line. Compiled code runs faster; interpreted code is easier to debug.  

5. **What is a hybrid approach to language translation (e.g., Java)?**  
   Java uses both a compiler and interpreter: code is compiled into *bytecode*, which is then interpreted by the Java Virtual Machine (JVM).  

6. **What is a linker?**  
   A linker combines compiled code files and libraries into a single executable program.  

7. **What is a preprocessor?**  
   A preprocessor modifies source code before compilation (e.g., `#include` in C adds library code).  

---

### **2. Execution Process**  
8. **What is source code?**  
   Source code is the human-readable program written in a high-level language (e.g., Python, C).  

9. **What is object code?**  
   Object code is machine-readable code produced by a compiler but not yet executable (requires linking).  

10. **What is machine code?**  
    Machine code is binary (0s and 1s) directly executed by the CPU.  

11. **Why do compiled languages need an executable file?**  
    The executable contains fully translated machine code ready to run without recompilation.  

12. **Why do interpreted languages not generate executables?**  
    Interpreted languages translate code at runtime, so no standalone file is created.  

---

### **3. Development Tools**  
13. **What is an IDE (Integrated Development Environment)?**  
    An IDE combines tools like a code editor, compiler, and debugger (e.g., Visual Studio, PyCharm).  

14. **What is a debugger?**  
    A debugger helps identify and fix errors by allowing step-by-step code execution and variable inspection.  

15. **What are build tools (e.g., Make, Gradle)?**  
    Build tools automate compiling, linking, and packaging code into executables.  

16. **What is version control (e.g., Git)?**  
    Version control tracks code changes, enabling collaboration and reverting to previous versions.  

---

### **4. Compiled vs. Interpreted Languages**  
17. **Give examples of compiled languages.**  
    C, C++, Rust, Go.  

18. **Give examples of interpreted languages.**  
    Python, JavaScript, Ruby.  

19. **What is Just-In-Time (JIT) compilation?**  
    JIT compiles code *during execution* for speed (used in Java, .NET).  

20. **Why might Python be slower than C++?**  
    Python is interpreted line by line, while C++ is precompiled to optimized machine code.  

---

### **5. Error Handling & Tools**  
21. **What is a syntax error?**  
    A syntax error occurs when code violates language rules (e.g., missing `:` in Python).  

22. **What is a runtime error?**  
    A runtime error occurs during execution (e.g., dividing by zero).  

23. **How does an interpreter help in debugging?**  
    It stops at the first error encountered, making it easier to locate issues.  

24. **What are breakpoints in debugging?**  
    Breakpoints pause code execution at specific lines to inspect variables and logic.  

---

### **6. Advanced Concepts**  
25. **What is cross-compilation?**  
    Compiling code on one system to run on another (e.g., compiling for Android on a Windows PC).  

26. **What is bytecode (e.g., Java, Python)?**  
    Bytecode is an intermediate code (not machine code) executed by a virtual machine (e.g., JVM).  

27. **What is garbage collection?**  
    Automatic memory management in languages like Java/Python to free unused memory.  

---

### **Category 8: Practical Scenarios**  
28. **When would you choose a compiled language over an interpreted one?**  
    For performance-critical tasks (e.g., game engines, operating systems).  

29. **Why might a beginner prefer an interpreted language like Python?**  
    Easier debugging, no compilation step, and simpler syntax.  

30. **What tool would you use to track changes in your code over time?**  
    **Version control systems** like Git.  
    
### **Category 1: Compilers**  
1. **What is a compiler?**  
   A compiler translates *entire source code* (e.g., C, C++) into machine code or an executable file **before** the program runs.  

2. **What are the key phases of a compiler?**  
   Lexical analysis, syntax parsing, semantic analysis, code optimization, and code generation.  

3. **Why do compiled programs run faster than interpreted ones?**  
   Compiled code is pre-optimized into machine code, while interpreted code is translated line by line during runtime.  

4. **What is a cross-compiler?**  
   A compiler that generates machine code for a different operating system or hardware (e.g., compiling Android apps on Windows).  

5. **What is an ahead-of-time (AOT) compiler?**  
   A compiler that translates code **before** runtime (e.g., C++ compilers), unlike JIT (Just-In-Time) compilers.  

---

### **Category 2: Interpreters**  
6. **What is an interpreter?**  
   An interpreter executes code line by line, translating and running it **during** runtime (e.g., Python, JavaScript).  

7. **Why are interpreters useful for debugging?**  
   They stop execution at the first error, making it easier to locate and fix bugs.  

8. **What is a scripting language?**  
   A language designed for quick execution and automation, often interpreted (e.g., Python, Ruby).  

9. **What is the downside of using an interpreter?**  
   Slower execution speed compared to compiled languages, as code is translated at runtime.  

---

### **Category 3: Hybrid Approaches**  
10. **How does Java use both compilation and interpretation?**  
    Java code is compiled into *bytecode*, which is then interpreted by the **JVM (Java Virtual Machine)**.  

11. **What is Just-In-Time (JIT) compilation?**  
    JIT compiles code into machine language **during runtime** to improve performance (used in Java, .NET).  

12. **What is bytecode?**  
    Intermediate code that is not machine-specific (e.g., Java `.class` files, Python `.pyc` files).  

---

### **Category 4: Development Tools**  
13. **What is an IDE?**  
    An **Integrated Development Environment** (e.g., Visual Studio, PyCharm) combines tools like editors, compilers, and debuggers.  

14. **What is a debugger?**  
    A tool for pausing code execution, inspecting variables, and fixing errors (e.g., breakpoints in VS Code).  

15. **What is a build tool (e.g., Make, Gradle)?**  
    A tool that automates compiling, linking, and packaging code into executables.  

16. **What is a linter?**  
    A tool that analyzes code for stylistic and syntax errors (e.g., ESLint for JavaScript).  

---

### **Category 5: Execution & Errors**  
17. **What is a syntax error?**  
    An error caused by violating language rules (e.g., missing semicolons in C).  

18. **What is a logical error?**  
    A bug where code runs but produces incorrect results (e.g., wrong formula in a calculation).  

19. **What is a runtime error?**  
    An error that occurs during execution (e.g., dividing by zero).  

20. **How does a linker work?**  
    It combines compiled code files and libraries into a single executable.  

---

### **Category 6: Advanced Tools & Concepts**  
21. **What is a disassembler?**  
    A tool that converts machine code back to assembly language for analysis.  

22. **What is static vs. dynamic typing?**  
    - **Static typing**: Variable types are checked at compile time (e.g., Java).  
    - **Dynamic typing**: Types are checked at runtime (e.g., Python).  

23. **What is garbage collection?**  
    Automatic memory management in languages like Java/Python to free unused memory.  

24. **What is a profiler?**  
    A tool that measures program performance (e.g., CPU/memory usage) to optimize code.  

---

### **Category 7: Revision Questions**  
25. **Re-ask: What is the difference between a compiler and an interpreter?**  
26. **Re-ask: Give two examples of compiled and interpreted languages.**  
27. **Re-ask: Why might Python be slower than C++?**  

---

### **Category 8: Practical Scenarios**  
28. **When would you choose a compiled language over an interpreted one?**  
    For performance-critical tasks (e.g., game engines, operating systems).  

29. **Why might a beginner prefer an interpreted language like Python?**  
    Easier debugging, no compilation step, and simpler syntax.  

30. **What tool would you use to track changes in your code over time?**  
    **Version control systems** like Git.  

---

### **7. Revision Questions**  
28. What is the role of a compiler? 
29. How does an interpreter work?
30. What is the purpose of an IDE?