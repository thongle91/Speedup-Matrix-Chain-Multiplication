# Usage

The input file contains 2 lines:

Line 1: n

Line 2: weights

### Example:

####input:

5

100 1 50 20 1

This is the product of 4 matrices M1(100x1), M2(1x50), M3(50x20), M4(20x1).

####ouput: 

1120 

That is the optimal cost by multiplying (M1x((M2xM3)xA4)).

## How to run

>> python speedup_topdown.py < input.txt
