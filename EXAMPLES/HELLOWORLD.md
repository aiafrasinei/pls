# HELLO WORLD

Classic hello world program for comparison

assembly:

``` asm
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

fortran:

``` fortran
program hello
  print *, 'Hello, World!'
end program hello
```

cobol:

``` cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. IDSAMPLE.
ENVIRONMENT DIVISION.
PROCEDURE DIVISION.
    DISPLAY 'HELLO WORLD'.
    STOP RUN.
```

lisp:

``` lisp
(print "Hello world!")
```

basic:

``` basic
PRINT "Hello World!"
```

bash:

``` bash
echo "Hello World!"
```

forth:

``` forth
." Hello world!"
```

c:

``` c
#include <stdio.h>

int main(int argc, char *argv[]) {
  print("Hello World!\n");
  return 0;
}
```

java:

``` java
class Main {
  public static void main(String[] args) {
    System.out.println("Hello World!");
  }
}
```

javascript:

``` javascript
console.log("Hello world!")
```

python:

``` python
print("Hello world!")
```

ruby:

``` ruby
puts "Hello World!"
```

lua:

``` lua
  print "Hello world!"
```
