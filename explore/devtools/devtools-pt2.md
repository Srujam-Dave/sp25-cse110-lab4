## 1

The bug was in the calculateSum function - the data type of the two numbers was
a string, so adding them concatenated the strings together. 

## 2

I'd fix the bug by manually converting the parameters of calculateSum to ints
so that they'd add together properly.