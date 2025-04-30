### 1

The print statement on line 9 prints "values added: 20".

### 2

The print statement on line 13 prints "final result: 20".

### 3

The var keyword should be avoided because it can lead to bugs and issues with
variables being redefined. Specifically, if the "values added" and "final 
result" were calculated separately, the values could interfere with each other.

### 4

The print statement on line 9 prints "values added: 20"

### 5

The line gives an error. This is because the print statement tries to access
the result variable outside of the `if` statement, which is the scope of the
result keyword, since it's defined with the `let` keyword.

### 6

This line gives an error. It attempts to assign a new value to result, which is
prohibited because it's defined with the `const` keyword on line 5.

### 7

Line 13 gives an error. This is because the line is attempting to access the
result variable outside of its scope, which is limited to the `if` block
because of the usage of the `const` keyword.