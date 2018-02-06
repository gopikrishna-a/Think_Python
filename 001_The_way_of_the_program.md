### The Python programming language


#### 1. What is Python?
**Ans:** Python is an example of a high-level language, Other high-level languages are C, C++, Perl, and Java.
There are also low-level languages, sometimes referred to as “machine languages” or “assembly languages.” Loosely speaking, computers can only run programs written in lowlevel languages. So programs written in a high-level language have to be processed before they can run. This extra processing takes some time, which is a small disadvantage of high-level languages.

The advantages are enormous. First, it is much easier to program in a high-level language. Programs written in a high-level language take less time to write, they are shorter and easier to read, and they are more likely to be correct. Second, high-level languages are portable, meaning that they can run on different kinds of computers with few or no modifications. Low-level programs can run on only one kind of computer and have to be rewritten to run on another.


#### 2. Interpreter and Compiler

+ Two kinds of programs process high-level languages into low-level languages:

![Interpreter Vs Compiler](https://i.imgur.com/v8tyajf.png)

#### 2.1 Interpreter

**Ans:** An interpreter reads a high-level program and executes it, meaning that it does what the program says. It processes the program a little at a time, alternately reading lines and performing computations. Figure 1.1 shows the structure of an interpreter.

#### 2.2 Compiler

**Ans:** A compiler reads the program and translates it completely before the program starts running. In this context, the high-level program is called the source code, and the translated program is called the object code or the executable. Once a program is compiled, you can execute it repeatedly without further translation. Figure 1.2 shows the structure of a compiler.

**Note:** Python is considered an interpreted language because Python programs are executed by an interpreter.

#### 3. What is a program?

**Ans:**  A program is a sequence of instructions that specifies how to perform a computation.

+ The details look different in different languages, but a few basic instructions appear in just about every language:
**input:** Get data from the keyboard, a file, or some other device.
**output:** Display data on the screen or send data to a file or other device.
**math:** Perform basic mathematical operations like addition and multiplication.
**conditional execution:** Check for certain conditions and execute the appropriate code.
**repetition:** Perform some action repeatedly, usually with some variation.

#### 4. What is debugging?

**Ans:** Programming is error-prone. For whimsical reasons, programming errors are called bugs and the process of tracking them down is called debugging.

Three kinds of errors can occur in a program: syntax errors, runtime errors, and semantic errors. It is useful to distinguish between them in order to track them down more quickly.

#### 4.1 Syntax errors

**Ans:** Python can only execute a program if the syntax is correct; otherwise, the interpreter displays an error message. Syntax refers to the structure of a program and the rules about that structure

#### 4.2 Runtime errors

**Ans:** The second type of error is a runtime error, so called because the error does not appear until after the program has started running. These errors are also called exceptions because they usually indicate that something exceptional (and bad) has happened.

#### 4.3  Semantic errors

**Ans:** The third type of error is the semantic error. If there is a semantic error in your program, it will run successfully in the sense that the computer will not generate any error messages, but it will not do the right thing. It will do something else. Specifically, it will do what you told it to do.

The problem is that the program you wrote is not the program you wanted to write. The meaning of the program (its semantics) is wrong. Identifying semantic errors can be tricky because it requires you to work backward by looking at the output of the program and trying to figure out what it is doing

#### 5. The first program

Traditionally, the first program you write in a new language is called “Hello, World!” because all it does is display the words “Hello, World!”. In Python, it looks like this

Program to print Hello, World!

    print('Hello, World!')









