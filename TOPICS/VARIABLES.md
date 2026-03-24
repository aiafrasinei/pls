# VARIABLES

Variables declaration, assignement, scope

* **ada**
``` ada
age : Integer := 2
a,b : Integer := 0
```

* **assembly**
* **awk**

``` awk
BEGIN {
    text="Test"
    age=2
}
{

}
END {

}
```

* **bash**

``` bash
text="Test"
age=2
prime=false
```

* **BASIC**

``` BASIC
STR = "Test"
AGE = 2
```

* **C**

``` C
char text[] = "Test";
int age = 2;
float angle = 2.0f;
```

* **COBOL**
* **forth**

``` forth
VARIABLE age
25 age !
age @ .

! - store
@ - fetch
```

* **fortran**

``` fortran
character :: text
integer :: age
real :: angle

text = "Test"
age = 2
angle = 3.0
```

* **go**

``` go
var text string = "Test"
var age int = 2 
var isPrime bool = true

//type inference
text := "Test"
age := 2
angle := 2.0
```

* **haskell**
* **java**

``` java
String text = "Test";
int age = 2;
float angle = 2.0f;
boolean isPrime = true;

//type inference
var test = "String";
```

* **javascript**

``` javascript
Local Function Global

local variables:
let text = "Test"
let age = 2
angle = 2.0f

available in the function where it was declared:
var text = "Test"
var age = 2
var angle = 2.0f
```

* **julia**

``` julia
text = "Test"
age = 2
```

* **lisp**

``` lisp
(defvar age 2)
(setq age 10)
(let ((str "Hello, world!"))
  (string-upcase str))
```

* **lua**

``` lua
text = "Test"
age = 2
angle = 2.0f
prime = true

default global (var appears on assignment no declaration)
local variable
```

* **ml**

``` ml
val n : int = 2
val text : string = "Test"

//type inference
val text = "Test"
```

* **pascal**

``` pascal
text: string = "Text"
age: integer = 2;
angle: real = 2.0;
```

* **perl**

``` perl
$text = "Text";
$age = 2;
```

* **php**

``` php
$text = "Text";
$age = 2;
```

* **prolog**
* **python**

``` python
text = "Test"
age = 2
angle = 2.0

global variable
```

* **R**

``` R
text <- "Text"
age <- 2
```

* **ruby**

``` ruby
text = "Test"
age = 2
angle = 2.0f

_ - local variable
$ - global variable
@ - instance variable
@@ - class variable
```

* **rust**

``` rust
let text = "Test"
let mut age = 5;
age = 6
let angle: f32 = 2.0;
let f: bool = false;

//type inference
let f = true;
```

* **swift**

``` swift
var text = "Test"
var text: String
var age: Int = 2
var angle: Double = 2.0 

//type inference
text = "Test"
age = 2
```

* **tcl**

``` tcl
set text = "Test"
set age = 2
```