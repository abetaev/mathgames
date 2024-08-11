[source](https://www.scientificamerican.com/game/math-puzzle-anna-birthday/)

given
=====

On her birthday in 2021, Anna reached an age in years equal to the sum of the digits of her birth year. In addition, Anna was less than 100 years old in 2021. In what years could she have been born?

`x=2021-abcd`
`x=a+b+c+d`
`x<100`

find x
======

inferred constraints
--------------------

`x=2021-1000a-100b-10c-d`
`x=a+b+c+d`

`a+b+c+d=2021-1000a-100b-10c-d`

`1001a+101b+11c+2d=2021`
`a`, `b`, `c`, `d` are `integers` in range `[0; 9]`

`a` can be `0`, `1` or `2`

hyp1: `a = 0`
-------------
            
`101b+11c+2d=2021`
`c=9` => `101b+2d=1922`

> **impossible!**


hyp2: `a = 1`
-----------

`101b+11c+2d=1020`

### hyp2.1: `b = 9`

`11c+2d=111`

#### hyp2.1.1: `c = 9`

`2d=12` => `d=6`

check:
`1+9+9+6=25`
`2021-1996=25`

#### hyp2.1.2: `c = 8`

`2d=13` (impossible)

#### hyp2.1.3: `c = 7`

`2d=24` (impossible)

### hyp2.2: `b = 8`

impossible

hyp3: `a = 2`
-------------

`101b+11c+2d=19` => `b=0`

`c` can be `0` or `1`

### hyp3.1: `c = 0`

`2d=19` (impossible)

### hyp3.2: `c = 1`

`2d=8` => `d=4`

check:
`2+0+1+4=7`
`2021-2014=7`

answer
======

`x` can be `1996` and `2014`
