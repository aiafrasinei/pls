# HOWTO forth

implementations:

gforth
https://www.gnu.org/software/gforth/

pforth
https://github.com/philburk/pforth

### manuals:

http://www.softsynth.com/pforth/pf_ref.php
https://www.complang.tuwien.ac.at/forth/gforth/Docs-html/


execute file like a script:
gforth hello.fs -e bye

### words:
.s
print stack , no distructive

.
print and remove last element in the stack

### comments:
\ comment
( )

### arithmetics:
+ - / * mod

### stack manipulation:
DUP (x - xx)
DROP (x -)
SWAP (x1 x2 - x2 x1)
OVER (x1 x2 - x1 x2 x1)
ROT (x1 x2 x3 - x2 x3 x1)
-ROT (x1 x2 x3 - x3 x1 x3)

2DUP (x1 x2 - x1 x2 x1 x2)
2DROP (x1 x2 -)
2SWAP (x1 x2 x3 x4 - x3 x4 x1 x2)
2OVER (x1 x2 x3 x4 - x1 x2 x3 x4 x1 x2)

### for with index
: COUNT-UP
    10 0 DO i . LOOP ;

: COUNT-DOWN
    0 10 DO i . -1 +LOOP ;
