# Truth-Table-Generator
## Operators
- '-' : Negation Operator
- '&' : AND Operator
- '|' : OR Operator
- '>' : Implication Operator
- '=' : If And Only If Operator
- '^' : XOR Operator

## Sample Input
-(((a & (b > c)) | b) ^ a)
[^1][^2]

## Sample Output
a b c Result  \
T T T &nbsp;&nbsp; T \
T T F &nbsp;&nbsp; T \
T F T &nbsp;&nbsp; T \
T F F &nbsp;&nbsp; T \
F T T &nbsp;&nbsp; F \
F T F &nbsp;&nbsp; F \
F F T &nbsp;&nbsp; T \
F F F &nbsp;&nbsp; T 

[^1]: Any letter in English alphabet (uppercase or lowercase) can be used as variables.
[^2]: You must use paranthesis around every operation (e.g., type "(a&b)" instead of "a&b").
