# Homework — Factorial Calculator

## Overview

In this assignment, you will create a Java program that calculates the factorial of a number using a loop.


You will practice:

- `for` loops
- Accumulator variables
- Multiplication
- User input
- `Scanner`

---

## Learning Objectives

By completing this assignment, you should be able to:

1. Use a `for` loop to perform repeated calculations.
2. Use an accumulator variable for multiplication.
3. Read an integer from the user using `Scanner`.
4. Calculate a factorial.
5. Store a calculated result in a variable.

---

## Problem Description

Create a Java program named:

```text
FactorialCalculator.java
```

The program should ask the user to enter a non-negative integer and then calculate its factorial.

The factorial of a number `n` is the product of all positive integers from `1` through `n`.

For example:

```text
5! = 5 × 4 × 3 × 2 × 1
```

Therefore:

```text
5! = 120
```

---

## Requirements

### 1. Class Name

Your Java file must be named:

```text
FactorialCalculator.java
```

The class must be named:

```java
FactorialCalculator
```

### 2. Main Method

Your program must contain:

```java
public static void main(String[] args)
```

### 3. Import Scanner

Include:

```java
import java.util.Scanner;
```

Create a `Scanner` object connected to standard input.

### 4. Number Variable

Create an `int` variable named:

```text
number
```

Use the `Scanner` to allow the user to enter the value.

### 5. Factorial Variable

Create a `long` variable named:

```text
factorial
```

Initialize it to `1`:

```java
long factorial = 1;
```

### 6. Calculate the Factorial

Use a `for` loop to calculate the factorial.

For a number such as `5`, the loop should perform:

```text
1 × 2 × 3 × 4 × 5
```

The result should be:

```text
120
```

The calculation must be performed in a loop. Do not hard-code the result.

---

## Required Output

For an input of `5`, your program must produce output similar to:

```text
Enter a non-negative integer: 5
Factorial: 120
```

---

---

## Loop Requirements

You must use a `for` loop to calculate the factorial.

Do not manually calculate the factorial using statements such as:

```java
factorial = 1 * 2 * 3 * 4 * 5;
```

The loop must perform the repeated multiplication.

---

---

## Data Type

Use a `long` for `factorial`:

```java
long factorial = 1;
```

The input `number` should be an `int`.

---

## Restrictions

For this assignment:

- Do not use arrays.
- Do not use `ArrayList`.
- You must use `Scanner`.
- You must use a `for` loop.
- You must calculate the factorial using the loop.
- Do not hard-code factorial results.
- Do not use recursion.

The purpose of this assignment is to practice loops and accumulator variables.

---

## Input Assumption

You may assume that the user enters a non-negative integer.

You do not need to implement input validation for negative numbers in this assignment.

---

## How to Compile

Open a terminal in the directory containing `FactorialCalculator.java`.

Compile:

```bash
javac FactorialCalculator.java
```

---

## How to Run

Run the program using:

```bash
java FactorialCalculator
```

---

## Submission

Your repository should contain:

```text
FactorialCalculator.java
```

Commit and push your work to your GitHub Classroom repository.


---

## Before You Submit

Make sure that:

- [ ] The file is named exactly `FactorialCalculator.java`.
- [ ] The class is named exactly `FactorialCalculator`.
- [ ] The program contains the required `main` method.
- [ ] `java.util.Scanner` is imported.
- [ ] A `Scanner` object is created.
- [ ] The user is prompted to enter a number.
- [ ] A `for` loop is used to calculate the factorial.
- [ ] The factorial is calculated by the program.
- [ ] The program correctly calculates `0!` as `1`.
- [ ] The program does not use recursion.
- [ ] The program does not use arrays.
- [ ] The program compiles without errors.
- [ ] The program produces the correct factorial.

## Submission Reminder

Do not modify the required file name or class name.

Your final submission should be:

```text
FactorialCalculator.java
```
