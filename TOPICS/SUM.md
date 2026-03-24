# SUM

A function for the sum of 2 numbers

* **ada**

``` ada
function sum (a,b : Integer) return Integer
is
begin
   return a + b;
end Func;
```

* **assembly**

``` asm
```

* **awk**

``` awk
function sum(a, b) {
    return a + b
}
```

* **bash**

``` bash
sum() {
    $(($1+$2))
}
```

* **BASIC**

``` BASIC
10 LET A = 15
20 LET B = 25
30 GOSUB 100
40 PRINT "THE SUM IS "; C
50 END

100 REM --- SUM SUBROUTINE ---
110 LET C = A + B
120 RETURN
```

* **C**

``` C
int sum(int a, int b) {
    return a + b;
}
```

* **COBOL**

``` C
IDENTIFICATION DIVISION.
PROGRAM-ID. SUM-PROGRAM.

DATA DIVISION.
WORKING-STORAGE SECTION.
01 A    PIC 9(4) VALUE 15.
01 B    PIC 9(4) VALUE 25.
01 TOTAL   PIC 9(5).

PROCEDURE DIVISION.
MAIN-PROCEDURE.
    ADD A TO B GIVING TOTAL.
    DISPLAY "THE SUM IS: " TOTAL.
    STOP RUN.
```

* **forth**

``` forth
: sum ( a b -- sum )
  + ;
```

* **fortran**

``` fortran
integer function sum(a, b)
    integer, intent(in) :: a, b
    sum = a + b
end function sum
```

* **go**

``` go
func sum(a, b int) (int) {
    return a + b
}
```

* **haskell**

``` haskell
sum :: Int -> Int -> Int
sum x y = x + y
```

* **java**

``` java
int sum(int a, int b) {
    return a + b;
}
```

* **javascript**

``` javascript
function sum(a, b) {
    return a + b;
}
```

* **julia**

``` julia
function sum(a, b)
    return a + b
end
```

* **lisp**

``` lisp
(defun sum (a b)
  (+ a b))
```

* **lua**

``` lua
function lua(a, b)
    return a + b
end
```

* **ml**

``` ml
fun sum x y = x + y;
```

* **pascal**

``` pascal
function sum(a, b: Integer): Integer;
begin
  sum := a + b;
end;
```

* **perl**

``` perl
sub sum {
    my ($a, $b) = @_;
    return $a + $b;
}
```

* **php**

``` php
function sum($a, $b) {
    return $a + $b;
}
```


* **prolog**
* **python**

``` python
def sum(a, b):
    return a + b
```

* **R**

``` R
sum <- function(b) {
  num1 + num2
}
```

* **ruby**

``` ruby
def sum(a, b)
  a + b
end
```

* **rust**

``` rust
fn sum(a: u32, b: u32) -> u32 {
    return a + b;
}
```

* **swift**

``` swift
func sum(a: Int, b: Int) -> Int {
    a + b
}
```

* **tcl**

``` tcl
proc sum {a b} {
    return [expr {$a + $b}]
}
```