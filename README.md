# DotNetBootcamp.LabExercise6

## Instructions
   Given a `Word`, compute the `Scrabble Score` for that `Word`.
## Letter Values
   You'll need these:
```
Letter                           Value
A, E, I, O, U, L, N, R, S, T       1
D, G                               2
B, C, M, P                         3
F, H, V, W, Y                      4
K                                  5
J, X                               8
Q, Z                               10
```
## Examples
   "cabbage" should be scored as worth 14 points:
   - 3 points for C
   - 1 point for A, twice
   - 3 points for B, twice
   - 2 points for G
   - 1 point for E
   
   And to `Total`:
   - = 3 + 2*1 + 2*3 + 2 + 1
   - = 3 + 2 + 6 + 3
   - = 5 + 9
   - = 14

## Exception Handling:
   - `Whitespaces` e.g. Hello World, __Hello___
   - `Special Characters` ~,./~!@#$%^&*()_+
   - `Numbers` 1234567890
