# HELLO WORLD

Classic hello world program for comparison


* **assembly**

``` assembly
;hello.asm
section .data
    msg db  "hello world",0
section .bss
section .text
    global main
main:
    mov rax, 1      ; 1 = write
    mov rdi, 1      ; 1 = to stdout
    mov rsi, msg    ; string to display in rsi
    mov rdx, 12     ; length of string without 0
    syscall         ; display the string
    mov rax, 60     ; 60 = exit
    mov rdi, 0      ; 0 = success exit code
    syscall         ; quit
```

* **awk**

``` awk
BEGIN {
  print "Hello World!"
}
```

* **bash**

``` bash
echo "Hello World!"
```

* **BASIC**

``` BASIC
PRINT "Hello World!"
```

* **C**

``` C
#include <stdio.h>

int main(int argc, char *argv[]) {
  print("Hello World!\n");
  return 0;
}
```

* **COBOL**

``` COBOL
IDENTIFICATION DIVISION.
PROGRAM-ID. IDSAMPLE.
ENVIRONMENT DIVISION.
PROCEDURE DIVISION.
    DISPLAY 'HELLO WORLD'.
    STOP RUN.
```

* **forth**

``` forth
." Hello world!"
```

* **fortran**

``` fortran
program hello
  print *, 'Hello, World!'
end program hello
```

* **go**

``` go
import "fmt"

func main() {
    fmt.Println("Hello World!")
}
```

* **haskell**

``` haskell
main = print "Hello World!"
```

* **java**

``` java
class Main {
  public static void main(String[] args) {
    System.out.println("Hello World!");
  }
}
```

* **javascript**

``` javascript
console.log("Hello world!")
```

* **julia**

``` julia
print("Hello World!")
```

* **lisp**

``` lisp
(print "Hello world!")
```

* **lua**

``` lua
print "Hello world!"
```

* **ml**

``` ml
print "Hello, World\n";
```

* **pascal**

``` pascal
program Hello;
begin
  writeln ('Hello World!');
end.
```

* **perl**

``` perl
print("Hello World!\n");
```

* **prolog**

``` prolog
:- initialization(main).
main :- write('Hello World!').
```

* **python**

``` python
print("Hello World!")
```

* **R**

``` R
print("Hello World!")
```

* **ruby**

``` ruby
puts "Hello World!"
```

* **rust**

``` rust
println!("Hello World!");
```

* **swift**

``` swift
print("Hello, World!")
```

* **tcl**

``` tcl
puts "Hello, World!"
```










