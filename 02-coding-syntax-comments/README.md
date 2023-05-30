# Coding Syntax and Comments in Different Languages

### Objectives:

* Learn how to use comments in your code.
* The entry point in various programming languages.
* The purpose of white space, line breaks, and code blocks in various programming languages.


You can find JuniorIT.AI's interactive content for this topic at
https://www.juniorit.ai/resource/blog/coding-syntax-and-comments-in-different-languages

## 1. Using Comments in Different Programming Languages

**Single Line Comments:**

In JavaScript/TypeScript, Dart, PHP, Python, Java, C++, Swift, Kotlin, Objective-C and Golang, single line comments are made using //. Everything on the same line after // is considered a comment.

**Multi-line Comments:**

In JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, multi-line comments are enclosed between /* and */.

> For demo purposes, the code below will be automatically added a main function if necessary when running.

Dart
```dart
// Single line comment
print("Hello, World!"); // comment

/*
Multi-line comment
The code below will print
"Hello, JuniorIT.AI!"
*/
print("Hello, JuniorIT.AI!"); /* comment */

print(123 /* a number */);

```

JavaScript/TypeScript
```javascript
// Single line comment
console.log("Hello, World!"); // comment

/*
Multi-line comment
The code will print
"Hello, JuniorIT.AI!"
*/
console.log("Hello, JuniorIT.AI!"); /* comment */

console.log(123 /* a number */)

```

PHP
```php
// Single line comment
echo "Hello, World!"; // comment

# This also is a single line comment
echo "Hi, World!"; # comment

/*
Multi-line comment
The code below will print
"Hello, JuniorIT.AI!"
*/
echo "Hello, JuniorIT.AI!"; /* comment */
echo 123 /* a number */;

```

Java
```java
// Single line comment
System.out.println("Hello, World!"); // comment

/*
Multi-line comment
The code below will print
"Hello, JuniorIT.AI!"
*/
System.out.println("Hello, JuniorIT.AI!"); /* comment */
System.out.println(123 /* a number */);

```

Kotlin
```kotlin
// Single line comment
println("Hello, World!") // comment

/*
Multi-line comment
The code below will print
"Hello, JuniorIT.AI!"
*/
println("Hello, JuniorIT.AI!") /* comment */
println(123 /* a number */)
```

C/C++
```c++
// # symbol is preprocessor directive, not comment
#include <stdio.h>

int main() {
    // Single line comment
    printf("Hello, World!\n"); // comment

    /*
    Multi-line comment
    The code below will print
    "Hello, JuniorIT.AI!"
    */
    printf("Hello, JuniorIT.AI!\n");  /* comment */

    printf("%d\n", 123  /* a number */);
}
```

Objective-C
```objective-c
// # symbol is preprocessor directive, not comment
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    NSAutoreleasePool * pool = [[NSAutoreleasePool alloc] init];

    // Single line comment
    NSLog(@"Hello, World!"); // comment

    /*
    Multi-line comment
    The code below will print
    "Hello, JuniorIT.AI!"
    */
    NSLog(@"Hello, JuniorIT.AI!"); /* comment */
    NSLog(@"%d",  123  /* a number */);

    [pool drain];
    return 0;
}
```

Swift
```swift
// Single line comment
print("Hello, World!") // comment

/*
Multi-line comment
The code below will print
"Hello, JuniorIT.AI!"
*/
print("Hello, JuniorIT.AI!") /* comment */
print(123 /* a number */)

```

Golang
```go
// Single line comment 
fmt.Println("Hello, World!") // comment

/*
Multi-line comment
The code below will print
"Hello, JuniorIT.AI!"
*/
fmt.Println("Hello, JuniorIT.AI!") /* comment */
fmt.Println(123 /* a number */)
```

**Python Specific:**

Python uses # for single line comments. For multi-line comments, Python typically uses triple quotes ''' or """, even though it's technically a string, not a comment.

Python
```python
# Single line comment
print("Hello, World!") # comment here

''' It's technically a string
Multi-line comment
The code below will print
"Hello, JuniorIT.AI!" 
'''
print("Hello, JuniorIT.AI!") # comment here

''' This is a comment '''

"""
This is a multi-line comment
"""

""" This is a comment """

```

PHP can use # for single line comments too.

In C, C++, and Objective-C, the # symbol is primarily used for preprocessor directives. We will talk this later.

**Guiding AI**

> We use comments to instruct AI to calculate the area of a triangle in different languages

Dart
```dart
import 'dart:math';

void main() {
    /*
    The length of each side of a triangle 
    L1 = 5.0 cm
    L2 = 8.6 cm
    L3 = 9.3 cm

    Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.

    */
}
```

JavaScript
```javascript

/*
The length of each side of a triangle 
L1 = 5.0 cm
L2 = 8.6 cm
L3 = 9.3 cm

Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.

*/
```
PHP
```php 
<?php
/*
The length of each side of a triangle 
L1 = 5.0 cm
L2 = 8.6 cm
L3 = 9.3 cm

Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.

*/

?>
```

Python
```python

'''
The length of each side of a triangle 
L1 = 5.0 cm
L2 = 8.6 cm
L3 = 9.3 cm

Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.

'''

```

Java
```java
public class HelloWorld {
  public static void main(String[] args) {
    /*
    The length of each side of a triangle 
    L1 = 5.0 cm
    L2 = 8.6 cm
    L3 = 9.3 cm

    Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.

    */
  }
}
```

Kotlin
```kotlin

fun main() {

    /*
    The length of each side of a triangle 
    L1 = 5.0 cm
    L2 = 8.6 cm
    L3 = 9.3 cm

    Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.

    */
}

```

Objective-C
```objective-c 
#import <Foundation/Foundation.h>

int main (int argc, const char * argv[]) {
   NSAutoreleasePool * pool = [[NSAutoreleasePool alloc] init];

    /*
    The length of each side of a triangle 
    L1 = 5.0 cm
    L2 = 8.6 cm
    L3 = 9.3 cm

    Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.
    */

   [pool drain];
   return 0;
}
```

Swift
```swift
// import math function
import Foundation

// The length of each side of a triangle 
// L1 = 5.0 cm
// L2 = 8.6 cm
// L3 = 9.3 cm

// Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.


```

C++
```cpp
#include <stdio.h>
#include <math.h>

int main() {

    /*
    The length of each side of a triangle 
    L1 = 5.0 cm
    L2 = 8.6 cm
    L3 = 9.3 cm

    Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.
    */

    return 0;
}
```

Golang
```go 
package main

import "fmt"
import "math"

func main() {
    /*
    The length of each side of a triangle 
    L1 = 5.0 cm
    L2 = 8.6 cm
    L3 = 9.3 cm

    Create a function that calculates the area of a triangle. Afterwards, utilize this function to determine the area of the above triangle, and display the resulting value.
    */
}

```

In short, comments provide extra information about your code, helping both you and others to understand it better.

## 2. Understanding the 'Main' Function as the Entry Point in Different Programming Languages  

When you write a program, you need to tell the computer where to start executing your code. This is called the entry point or starting point. In most programming languages, the entry point is a function called main().

**Languages with Explicit Main Functions:**

Dart, Kotlin, Java, C/C++, Objective-C and Golang all have explicit main functions that serve as the entry point of a program. In these languages, the main function is where your program begins executing commands.

Dart
```dart
// Define the main function.
void main() {
  // This is where your program starts executing.

  // Print 'Hello, World!' to the console.
  print('Hello, World!');
}
```

Dart: code error
```dart 
// No main function is defined in Dart. It will result in an error when run.

// Print 'Hello, World!' to the console.
print('Hello, World!');

```

Kotlin
```kotlin
// Define the main function.
fun main() {
    // This is where your program starts executing.

    // Print 'Hello, World!' to the console.
    println("Hello, World!")
}
```
Java
```java
// Define a public class. In Java, every application must contain a main class 
// that wraps up the main function.
public class Main {

    // Define the main function. The String array (String[]) parameter is used for command line arguments.
    public static void main(String[] args) {
        // This is where your program starts executing.

        // Print 'Hello, World!' to the console.
        System.out.println("Hello, World!");
    }
}
```

C 
```c
// Include the stdio.h library to enable input/output in our program.
#include <stdio.h>

// Define the main function.
// It returns an integer to signify the exit status of the program.
int main() {
    // This is where your program starts executing.

    // Print 'Hello, World!' to the console.
    printf("Hello, World!\n");

    // Return 0 to signify that the program has ended successfully.
    return 0;
}
```

C++
```c++
// Include the iostream library to enable input/output in our program.
#include <iostream>

// // Define the main function.
// It returns an integer to signify the exit status of the program.
int main() {
    // This is where your program starts executing.

    // Print 'Hello, World!' to the console.
    std::cout << "Hello, World!" << std::endl;

    // Return 0 to signify that the program has ended successfully.
    return 0;
}
```

Objective-C
```objective-c
// Import the Foundation library, which contains basic data types, collections and utilities.
#import <Foundation/Foundation.h>

// // Define the main function.
// It returns an integer to signify the exit status of the program.
int main(int argc, const char * argv[]) {
    // This is where your program starts executing.

    // It is used to manage the memory of objects
    NSAutoreleasePool* pool = [[NSAutoreleasePool alloc] init];
        
    // Print 'Hello, World!' to the console.
    NSLog(@"Hello, World!");

    // to release the memory associated with the NSAutoreleasePool object pointed to by pool.
    [pool drain];

    // Return 0 to signify that the program has ended successfully.
    return 0;
}
```

Golang
```go
package main

import "fmt"

// main is the entry point of the program
func main() {
	// Print "Hello, world!" to the console
	fmt.Println("Hello, world!")
}
```


**Languages with Different Conventions:**

Python doesn't have an explicit main function. However, in Python, a "main code" block can be created by placing it within an if __name__ == '__main__': clause. This ensures that the "main code" block is not executed when the file is imported as a module.

Python
```python
# This is a Python program with no explicit entry point
# The program starts executing from the first line

print("Hello, JuniorIT.AI!")

```

Python: having main code block
```python
# This is a Python program with no explicit entry point
# The program starts executing from the first line

print("This program starts from here.")

# Below is an if statement that checks whether the system variable __name__ is equal to '__main__'. If this condition evaluates to True, it implies that the current script is being run as the main program rather than being imported as a module. 

if __name__ == '__main__':
    print("You will not see this output if this file is imported as a module!")

```

**Languages with No Entry Points:**
JavaScript/TypeScript, PHP, Swift don't have an explicit main function or a special convention for defining the entry point. Instead, the program starts executing from the first line of the global scope of your code.

JavaScript

```javascript
// This is a JavaScript program with no explicit entry point
// The program starts executing from the first line

console.log("Hello, world!"); // Prints "Hello, world!" to the console
var x = 5; // Declares a variable 'x' and assigns it a value of 5
console.log(x); // Prints the value of 'x' (5) to the console
```

TypeScript
```typescript
// This is a TypeScript program with no explicit entry point
// The program starts executing from the first line

console.log("Hello, world!"); // Prints "Hello, world!" to the console
let x: number = 5; // Declares a variable 'x' of type number and assigns it a value of 5
console.log(x); // Prints the value of 'x' (5) to the console
```

PHP
```php 
<?php
// This is a PHP program with no explicit entry point
// The program starts executing from the first line

echo "Hello, world!\n"; // Prints "Hello, world!". The \n character is used to insert a new line.
$x = 5; // Assigns a value of 5 to variable 'x'
echo $x; // Prints the value of 'x' (5) to the output
?>
```

Swift
```swift
// This is a Swift program with no explicit entry point
// The program starts executing from the first line

print("Hello, world!") // Prints "Hello, world!" to the console
var x = 5 // Declares a variable 'x' and assigns it a value of 5
print(x) // Prints the value of 'x' (5) to the console
```

## 3. White Spaces and New Lines in Coding Syntax

In JavaScript/TypeScript, Dart, PHP, Java, Swift, Kotlin, C/C++, Objective-C and Golang, white spaces (like spaces and tabs) and new lines don't change your code's meaning, unless they're inside text (known as "strings").


Dart
```dart
// White spaces and new lines don't affect the code's meaning
// But the code becomes hard to read when white spaces and new lines are used improperly

void main() {
  int x=
  5;

  int y   =    10
  ;
  
  print(x 
        + y);

  // White spaces inside strings do affect the code's meaning
  String message = "Hello    World";
  print(message);
}

```

JavaScript
```javascript
// White spaces and new lines don't affect the code's meaning
// But the code becomes hard to read when white spaces and new lines are used improperly

let x=5
let y   =    
10

console.log(5 
            + 10)

// White spaces inside strings do affect the code's meaning
let message = "Hello    World"
console.log(message)
```

```typescript {}
// White spaces and new lines don't affect the code's meaning
// But the code becomes hard to read when white spaces and new lines are used improperly
let x: number = 5;

let y   :    number = 
   10;

console.log(5 
            + 10)


// White spaces inside strings do affect the code's meaning
let message: string = "Hello   World";
console.log(message);
```

PHP
```php
// White spaces and new lines don't affect the code's meaning
$x = 5;
$y   =    10;

echo $x +      $y;

// print a new line
echo "\n";

// White spaces inside strings do affect the code's meaning
$message = "Hello    World";
echo $message;
```

Java
```java
// White spaces and new lines don't affect the code's meaning
public class Main {
    public static void main(String[] args) {
        int x=5;
        int y   =    10;
        
        System.out.println(x + y);

        // White spaces inside strings do affect the code's meaning
        String message = "Hello     World";
        System.out.println(message);
    }
}

```

Swift
```swift
// White spaces and new lines don't affect the code's meaning
let x = 5
let y   =    10


// White spaces inside strings do affect the code's meaning
let message = "Hello     World"
print(message)
```

```kotlin {}
// White spaces and new lines don't affect the code's meaning
fun main() {
    val x = 5
    val y   =    10

    println(x + y)

    // White spaces inside strings do affect the code's meaning
    val message = "Hello     World"
    println(message)
}

```

C++
```c++
// White spaces and new lines don't affect the code's meaning
#include <iostream>

int main() {
    int x=5;
    int y   =    10;
    
    std::cout << x + y << std::endl;

    // White spaces inside strings do affect the code's meaning
    std::string message = "Hello     World";
    std::cout << message << std::endl;

    return 0;
}

```

Objective-C
```objective-c
// White spaces and new lines don't affect the code's meaning
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    NSAutoreleasePool* pool = [[NSAutoreleasePool alloc] init];

    int x=5;
    int y   =    10;
    
    NSLog(@"%d", x + y);

    // White spaces inside strings do affect the code's meaning
    NSString *message = @"Hello     World";
    NSLog(@"%@", message);

    [pool drain];
    return 0;
}
```

Golang
```go
// White spaces and new lines don't affect the code's meaning
package main

import "fmt"

func main() {
	x := 5
	y:=    10;
	
	fmt.Println(x + y);

    // White spaces inside strings do affect the code's meaning
    message := "Hello     World";
	fmt.Println(message);
}

```

Python is a bit different: it uses white spaces at the start of lines to group parts of your code together. New lines usually mean "this instruction is done," unless your code is inside brackets.


Python
```python
# Example 1: White Spaces

# Grouping code using indentation (4 spaces or a tab)
if True:
    print("This line is inside the if block.")  # Indented line
    print("This line is inside the if block.")  # Indented line

    print("This line is inside the if block.")  # Indented line

print("This line is outside the if block.")  # Not indented line

# Example 2: Strings and spaces

# Spaces and new lines count as part of the text inside strings
message = "Hello,            world!"  # Multiple spaces between Hello and world
print(message)

multiline_message = """This is a
multiline
message."""
print(multiline_message)
```

Python: code error
```python 
# Example 1: IndentationError

# Missing indentation within a block of code
if True:
print("Indented line without proper indentation.")  # Causes IndentationError

# Example 2: SyntaxError

# Inconsistent indentation within a block of code
if True:
    print("Line inside the if block.")
     print("Incorrect indentation causes SyntaxError.")  # Causes SyntaxError

# Example 3: SyntaxError

# Mixing spaces and tabs for indentation
if True:
    print("Line inside the if block.")
  print("Using both spaces and tabs for indentation causes SyntaxError.")  # Causes SyntaxError

```

In all these languages, inside strings, spaces and new lines count as part of the text.

## 4. Defining Code Blocks in Programming Languages

JavaScript/TypeScript, Dart, PHP, Java, Swift, Kotlin, C/C++, Objective-C and Golang use curly braces {} to group related lines of code together. These grouped lines, called code blocks, are often used in functions, loops, or conditionals.

> For demo purposes, the code below will be automatically added a main function if necessary when running.

Dart
```dart
// Curly braces {} are used to define code blocks
if (true) {
  // This is a code block
  print("The first 10 digits of pi (π) are:");
  print(3.1415926535);
}

// This is not a code block
print("Welcome to JuniorIT.AI!");
```

JavaScript/TypeScript
```
// Curly braces {} are used to define code blocks
if (true) {
  // This is a code block
  console.log("The first 10 digits of pi (π) are:");
  console.log(3.1415926535);
}

// This is not a code block
console.log("Welcome to JuniorIT.AI!");
```

PHP
```php
// Curly braces {} are used to define code blocks
if (true) {
  // This is a code block
  echo "The first 10 digits of pi (π) are:";
  echo 3.1415926535;
}

// This is not a code block
echo "Welcome to JuniorIT.AI!";
```

Java
```java
// Curly braces {} are used to define code blocks
if (true) {
  // This is a code block
  System.out.println("The first 10 digits of pi (π) are:");
  System.out.println(3.1415926535);
}

// This is not a code block
System.out.println("Welcome to JuniorIT.AI!");
```

Swift
```swift
// Curly braces {} are used to define code blocks
if true {
  // This is a code block
  print("The first 10 digits of pi (π) are:")
  print(3.1415926535)
}

// This is not a code block
print("Welcome to JuniorIT.AI!")
```

Kotlin
```kotlin
// Curly braces {} are used to define code blocks
if (true) {
  // This is a code block
  println("The first 10 digits of pi (π) are:")
  println(3.1415926535)
}

// This is not a code block
println("Welcome to JuniorIT.AI!")
```

C/C++
```c++ 
// Curly braces {} are used to define code blocks
if (true) {
  // This is a code block
  printf("The first 10 digits of pi (π) are:\n");
  printf("%.10f\n", 3.1415926535);
}

// This is not a code block
printf("Welcome to JuniorIT.AI!\n");
```

Objective-C
```objective-c
// Curly braces {} are used to define code blocks
if (true) {
  // This is a code block
  NSLog(@"The first 10 digits of pi (π) are:");
  NSLog(@"%.10f", 3.1415926535);
}

// This is not a code block
NSLog(@"Welcome to JuniorIT.AI!");

```

Golang
```go 
// Curly braces {} are used to define code blocks
if true {
  // This is a code block
  fmt.Println("The first 10 digits of pi (π) are:")
  fmt.Println(3.1415926535)
}

// This is not a code block
fmt.Println("Welcome to JuniorIT.AI!")

```

Python, however, uses indentation (spaces at the start of a line) to define its code blocks. Instead of curly braces, each group of indented lines forms a block, helping Python to understand which lines of code should be treated as a unit.

Python
```python
# Indentation is used to define code blocks in Python
if True:
  # This is a code block
  print("The first 10 digits of pi (π) are:")
  print(3.1415926535)

# This is not a code block
print("Welcome to JuniorIT.AI!")
```

## 5. Usage of Semicolons to End Lines in Programming Languages

**Mandatory:** Dart, PHP, Java, C/C++, Objective-C require semicolons ; at the end of each statement.

Dart
```dart
// Dart - semicolons are mandatory

void main() {
  // Single line statements
  var x = 10;
  var y = 20;
  var z = x + y;

  // Multiple statements on a single line (avoided in practice)
  var a = 5; var b = 7; var c = a * b;

  // Omitting semicolons at the end of lines causes errors
  print("The value of z is: $z")
  print("The value of c is: $c")
}

```

PHP
```
// PHP - semicolons are mandatory

// Single line statements
$x = 10;
$y = 20;
$z = $x + $y;

// Multiple statements on a single line (avoided in practice)
$a = 5; $b = 7; $c = $a * $b;

// Omitting semicolons at the end of lines causes errors
echo "The value of z is: " . $z . "\n"
echo "The value of c is: " . $c . "\n"
```

Java
```java
// Java - semicolons are mandatory

public class Main {
    public static void main(String[] args) {
        // Single line statements
        int x = 10;
        int y = 20;
        int z = x + y;

        // Multiple statements on a single line (avoided in practice)
        int a = 5; int b = 7; int c = a * b;

        // Omitting semicolons at the end of lines causes errors
        System.out.println("The value of z is: " + z)
        System.out.println("The value of c is: " + c)
    }
}

```

C/C++
``` c++
// C/C++ - semicolons are mandatory

#include <iostream>

int main() {
    // Single line statements
    int x = 10;
    int y = 20;
    int z = x + y;

    // Multiple statements on a single line (avoided in practice)
    int a = 5; int b = 7; int c = a * b;

    // Omitting semicolons at the end of lines causes errors
    std::cout << "The value of z is: " << z << std::endl
    std::cout << "The value of c is: " << c << std::endl

    return 0;
}

```

Objective-C
``` objective-c
// Objective-C - semicolons are mandatory

#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    NSAutoreleasePool* pool = [[NSAutoreleasePool alloc] init];

    // Single line statements
    int x = 10;
    int y = 20;
    int z = x + y;

    // Multiple statements on a single line (avoided in practice)
    int a = 5; int b = 7; int c = a * b;

    // Omitting semicolons at the end of lines causes errors
    NSLog(@"The value of z is: %d", z)
    NSLog(@"The value of c is: %d", c)

    [pool drain];

    return 0;
}

```

**Optional:**  JavaScript/TypeScript, Kotlin, Swift and Golang semicolons are technically optional at the end of statements. However, their use is often considered good practice for clarity and avoiding potential issues.


JavaScript
```javascript
// JavaScript - semicolons are technically optional

// Single line statements
var x = 10;
var y = 20;
var z = x + y;

// Multiple statements on a single line (avoided in practice)
var a = 5; var b = 7; var c = a * b;

// Please keep the coding style consistent when not using semicolons at the end of lines
console.log("The value of z is:", z)
console.log("The value of c is:", c)

```

TypeScript
```typescript
// TypeScript - semicolons are technically optional

// Single line statements
let x: number = 10;
let y: number = 20;
let z: number = x + y;

// Multiple statements on a single line (avoided in practice)
let a: number = 5; let b: number = 7; let c: number = a * b;

// Please keep the coding style consistent when not using semicolons at the end of lines
console.log("The value of z is:", z)
console.log("The value of c is:", c)

```

Kotlin
```kotlin
// Kotlin - semicolons are technically optional

fun main() {
    // Single line statements
    val x = 10
    val y = 20
    val z = x + y

    // Multiple statements on a single line (avoided in practice)
    val a = 5; val b = 7; val c = a * b

    // Please keep the coding style consistent when using semicolons at the end of lines
    println("The value of z is: $z");
    println("The value of c is: $c");
}

```

Swift
```swift
// Swift - semicolons are technically optional

// Single line statements
let x = 10
let y = 20
let z = x + y

// Multiple statements on a single line (avoided in practice)
let a = 5; let b = 7; let c = a * b

 // Please keep the coding style consistent when using semicolons at the end of lines
print("The value of z is: \(z)");
print("The value of c is: \(c)");

```

Golang
```go
package main

import "fmt"

// Go - semicolons are technically optional

func main() {
    // Single line statements
    x := 10
    y := 20
    z := x + y

    // Multiple statements on a single line (avoided in practice)
    a := 5; b := 7; c := a * b

    // Please keep the coding style consistent when using semicolons at the end of lines
    fmt.Println("The value of z is:", z);
    fmt.Println("The value of c is:", c);
}

```

**Not Required:** Python does not require semicolons to end statements.
Semicolons can be used to separate multiple statements on a single line, but this is not common practice.


Python
```python
# Python does not require semicolons to end statements

# Single line statements
x = 10
y = 20
z = x + y

# Multiple statements on a single line (uncommon practice)
a = 5; b = 7; c = a * b

# Ending with a semicolon doesn't treat as an error, but do not do this
print("The value of z is:", z);
print("The value of c is:", c);

```


## 6. Using Single and Double Quotes to Define Strings in Programming Languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

In Dart, JavaScript/TypeScript, PHP, Python, strings can be defined using either single quotes or double quotes. Both ways are equivalent, and the choice usually comes down to programmer's preference or to avoid escaping within the string.


Dart
```dart
// Defining a string using double quotes
String doubleQuotesString = "This is a string defined using double quotes.";
print(doubleQuotesString);

// Defining a string using single quotes
String singleQuotesString = 'This is a string defined using single quotes.';
print(singleQuotesString);

```

JavaScript/TypeScript
```javascript
// Defining a string using double quotes
const doubleQuotesString = "This is a string defined using double quotes.";
console.log(doubleQuotesString);

// Defining a string using single quotes
const singleQuotesString = 'This is a string defined using single quotes.';
console.log(singleQuotesString);
```

PHP
```php
// Defining a string using double quotes
$doubleQuotesString = "This is a string defined using double quotes.";
echo $doubleQuotesString;

// Defining a string using single quotes
$singleQuotesString = 'This is a string defined using single quotes.';
echo $singleQuotesString;

```

Python
```python
# Defining a string using double quotes
double_quotes_string = "This is a string defined using double quotes."
print(double_quotes_string)

# Defining a string using single quotes
single_quotes_string = 'This is a string defined using single quotes.'
print(single_quotes_string)
```

In languages like Java, Kotlin, C/C++, Objective-C, and Swift, and Golang strings are typically defined using double quotes. Single quotes are used to define character literals in Java, Kotlin, C/C++ and Objective-C.

In Go, character literals are represented using single quotes ('). However, Go does not have a dedicated character type like some other programming languages. Instead, characters in Go are represented using their corresponding Unicode code points, which are integer values.

java
```java
// Defining a string using double quotes
String doubleQuotesString = "This is a string defined using double quotes.";
System.out.println(doubleQuotesString);

// Single quotes are used for character literals
char singleQuotesChar = 'A';
System.out.println(singleQuotesChar);

```

Kotlin
```kotlin
// Defining a string using double quotes
val doubleQuotesString = "This is a string defined using double quotes."
println(doubleQuotesString)

// Single quotes are used for character literals
val singleQuotesChar = 'A'
println(singleQuotesChar)

```

C/C++
```c++ 
#include <iostream>
#include <string>

int main() {
    // Defining a string using double quotes
    std::string doubleQuotesString = "This is a string defined using double quotes.";
    std::cout << doubleQuotesString << std::endl;

    // Single quotes are used for character literals
    char singleQuotesChar = 'A';
    std::cout << singleQuotesChar << std::endl;

    return 0;
}
```

Objective-C
```objective-c
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    NSAutoreleasePool * pool = [[NSAutoreleasePool alloc] init];

    // Defining a string using double quotes
    NSString *doubleQuotesString = @"This is a string defined using double quotes.";
    NSLog(@"%@", doubleQuotesString);
        
    // Single quotes are used for character literals
    char singleQuotesChar = 'A';
    NSLog(@"%c", singleQuotesChar);

    [pool drain];
    return 0;
}

```

Swift
```swift
// Defining a string using double quotes
let doubleQuotesString = "This is a string defined using double quotes."
print(doubleQuotesString)

// Single quotes are used for character literals
let singleQuotesChar: Character = "A"
print(singleQuotesChar)

```

Golang
```go
package main

import "fmt"

func main() {
    // Defining a string using double quotes
    doubleQuotesString := "This is a string defined using double quotes."
    fmt.Println(doubleQuotesString)

    // Define a unicode character literal using single quotes
    unicode := 'A'
    fmt.Println(unicode)

    // To obtain the Unicode code point of a character, you can use the `rune` type
    codePoint := rune(unicode)
    fmt.Println(codePoint)
}

```

## 7. Basic Coding Formatting Guidelines

* **Indentation**: Use spaces (typically four) to show code structure. This makes your code easier to read.

* **Line Length**: Try to keep your lines short, ideally under 80 characters. This prevents horizontal scrolling and makes your code more viewable.

* **Blank Lines**: Use blank lines to separate sections of your code. This helps you see different parts more clearly.

* **Spacing with Operators and Commas**: Put spaces around operators (like `=` or `+`) and after commas. For example, `x = y + z` and `my_function(x, y, z)` are easier to read.

* **Avoid Trailing White Spaces**: Don't leave spaces at the end of lines. They don't add value and can make version control messy.

* **Spaces and Brackets**: Avoid spaces inside brackets. Write `my_function(x)`, not `my_function( x )`.

These guidelines help to make your code cleaner and more understandable. Remember to also check any style guides related to your specific programming language.

## 8. Other languages

- "Using code examples to explain Ruby language's syntax: white spaces, line breaks, comments and code block etc."
- "Using code examples to explain Rust language's syntax: white spaces, line breaks, comments and code block etc."
- "Using code examples to explain C# language's syntax: white spaces, line breaks, comments and code block etc."
- "Using code examples to explain Lua script's syntax: white spaces, line breaks, comments and code block etc."
- "Using code examples to explain Bash script's syntax: white spaces, line breaks, comments and code block etc."
