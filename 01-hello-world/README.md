# Let's explore the 'Hello World' project in some of the most popular coding languages.

You can find more details for this topic at
https://juniorit.ai/resource/blog/hello-world-in-different-coding-languages


### Objectives:

* To learn the concept of Hello World project, which is the first project for beginners in any coding language
* To know how to display strings or numbers on a computer's screen or console
* To gain an impression of the most popular coding languages currently used by various projects and companies

1. Dart
```dart
void main() {
  String greeting = 'Hello, World!';
  print(greeting);
  print('Hello, World!');
  print('JuniorIT' + '.AI');

  int num = 1234;
  print(num);
  print(1234);
  print(12 + 34);
}
```

2. Javascript
```javascript
let greeting = 'Hello, World!';
console.log(greeting);
console.log('Hello, World!');
console.log('JuniorIT' + '.AI');

let num = 1234;
console.log(num);
console.log(1234);
console.log(12 + 34);
```

3. Typescript
```typescript
let greeting: string = 'Hello, World!';
console.log(greeting);
console.log('Hello, World!');
console.log('JuniorIT' + '.AI');

let num: number = 1234;
console.log(num);
console.log(1234);
console.log(12 + 34);
```

4. Python
```python
greeting = 'Hello, World!'
print(greeting)
print('Hello, World!')
print('JuniorIT' + '.AI')

num = 1234
print(num)
print(1234)
print(12 + 34)
```
5. PHP
```php
$greeting = 'Hello, World!';
echo $greeting . "\n";
echo 'Hello, World!' . "\n";
echo 'JuniorIT' . '.AI' . "\n";

$num = 1234;
echo $num . "\n";
echo 1234 . "\n";
echo 12 + 34 . "\n";
```

6. Swift
```swift
let greeting: String = "Hello, World!"
print(greeting)
print("Hello, World!")
print("JuniorIT" + ".AI")

let num: Int = 1234
print(num)
print(1234)
print(12 + 34)
```

7. Java
```java
public class HelloWorld {
  public static void main(String[] args) {
    String greeting = "Hello, World!";
    System.out.println(greeting);
    System.out.println("Hello, World!");
    System.out.println("JuniorIT" + ".AI");

    int num = 1234;
    System.out.println(num);
    System.out.println(1234);
    System.out.println(12 + 34);
  }
}
```

8. Kotlin
```kotlin
fun main() {
  val greeting: String = "Hello, World!"
  println(greeting)
  println("Hello, World!")
  println("JuniorIT" + ".AI")

  val num: Int = 1234
  println(num)
  println(1234)
  println(12 + 34)
}
```

9. C 
```c
#include <stdio.h>

int main() {
  char greeting[] = "Hello, World!";
  printf("%s\n", greeting);
  printf("Hello, World!\n");
  printf("JuniorIT.Ai\n");

  int num = 1234;
  printf("%d\n", num);
  printf("%d\n", 1234);
  printf("%d\n", 12 + 34);

  return 0;
}
```

10. C++
```cpp
#include <iostream>
#include <string>
using namespace std;

int main() {
  string greeting = "Hello, World!";
  cout << greeting << endl;
  cout << "Hello, World!" << endl;
  cout << "JuniorIT" << ".AI" << endl;

  int num = 1234;
  cout << num << endl;
  cout << 1234 << endl;
  cout << 12 + 34 << endl;

  return 0;
}
```

11. Go
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

12. React framework (Typescript)
```typescript
import React, { useState, useEffect } from "react";

function App() {
  const [count, setCount] = useState(0);

  let message: string = 'Hello, World!';
  
  useEffect(() => {
    console.log(message);
    let timer = setInterval(() => {
      setCount((count) => count + 1);
    }, 1000);

    return () => clearInterval(timer);
  }, []);

  return (
    <>
      <h1>{count} times!</h1>
      <style jsx>{`
        h1 {
          color: red;
        }
      `}
      </style>
    </>
  );
}

export default App;
```

13. Flutter framework (dart)
```dart

import 'package:flutter/material.dart';

void main() {
  runApp(const HelloWorld());
}

class HelloWorld extends StatelessWidget {
  const HelloWorld({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return const MaterialApp(
      home: Center(child: Text('Hello World')),
    );
  }
}
``` 