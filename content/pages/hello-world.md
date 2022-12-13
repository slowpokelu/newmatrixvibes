---
title: "Hello World"
weight: 998
draft: false
---

in a variety of programming languages. Because Pog.


Python

```python
print("Hello, World!")
```

C

```c
#include <stdio.h>

int main() {
   printf("Hello, World!\n");
   return 0;
}
```

C++

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!\n";
    return 0;
}
```

Javascript

```javascript
console.log("Hello, World!");
```

Common Lisp

```common-lisp
(format t "Hello, World!")
```

Rust

```rust
fn main() {
    println!("Hello, World!");
}
```

Golang

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

NASM

```nasm
; Variables in the data section
SECTION .DATA
    hello:     db 'Hello world!',10
    helloLen:  equ $-hello

; Code in the text section
SECTION .TEXT
    GLOBAL _start

_start:
    mov eax,4            ; 'write' system call = 4
    mov ebx,1            ; file descriptor 1 = STDOUT
    mov ecx,hello        ; string to write
    mov edx,helloLen     ; length of string to write
    int 80h              ; call the kernel

    mov eax,1            ; 'exit' system call
    mov ebx,0            ; exit with error code 0
    int 80h              ; call the kernel
```

BASH and Nim

```bash
echo "Hello, World!"
```

Ruby

```ruby
puts "Hello, World!"
```

Haskell

```haskell
main :: IO ()
main = putStrLn "Hello, World!"
```

C#

```csharp
namespace HelloWorld
{
    class Hello {
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hello, World!");
        }
    }
}
```

F#

```fsharp
open System
printfn "Hello, World!"
```

Scala

```scala
object Hello {
    def main(args: Array[String]) = {
        println("Hello, World!")
    }
}
```

Julia

```julia
println("Hello, World!")
```
