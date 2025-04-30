## 1

At line 12, the value of i will be 3. While `i` is initialized at 0, it
increments to the length of `prices`, which is 3. Since `i` is initialized with
`var`, the scope extends across the whole function, so the value is still 3 
when the print statement is called. 

## 2

The print statement prints 150. This is because `discountedPrice` is
initialized with the `var` keyword, so the variable's scope extends through the
whole function. As a result, it is redefined with every iteration through the
loop until the last one, where it's set equal to `300 - (1 - 0.5) = 150`.

## 3

The print statement prints 150. This is because `finalPrice` is redefined every
pass through the loop until the final value of 150.

## 4

The function will return an array with values `[50, 100, 150]`. This is because
`finalPrice` takes on a new value every iteration of the loop, which is 0.5 
multiplied by the the `i`th value of `prices`. The value is then copied to the
`discounted` array.

## 5

The line gives an error. The scope of `i` is only inside the for loop because
of the `let` keyword used to define it. The print statement is outside the 
loop.

## 6

The line gives an error for identical reasons as part 5.

## 7

The print statement prints 150. Because `finalPrice` is defined outside of the
for loop, its scope is across the whole function. As the final iteration of the
for loop leaves the value of `finalPrice` at 150, this value remains when the
print statement is called.

## 8

The function returns the array `[50, 100, 150]`. As the for loop executes, the
value of `finalPrice` is changed to 0.5 times the corresponding element in
`prices`. As these values of `finalPrice` are pushed to `discounted`, copies of
the primitive values are added to the array. 

## 9

The line causes an error, since the print statement is outside `i`'s scope, 
which is the for loop.

## 10

The print statement prints "3". This is because prices has a length of 3.
The `length` variable is given the value 3, which remains until the print 
statement on line 12. 

## 11

The function also returns `[50, 100, 150]`. `discountedPrice` 

## 12

- name: `student.name`
- Grad Year: `student['Grad Year']`
- Greeting:  `student.greeting()`
- Favorite Teacher Name: `student['Favorite Teacher'].name`
- courseLoad Index: `student.courseLoad[0]`

## 13

- '3' + 2 = '32'
- '3' - 2 = 1
- 3 + null = 3
- '3' + null = '3null'
- true + 3 = 4
- false + null = 0
- '3' + undefined = '3undefined'
- '3' - undefined = NaN

## 14

- '2' > 1: true
- '2' < '12': false
- 2 == '2': true
- 2 === '2': false
- true == '2': false
- true == Boolean(2): true

## 15

While `==` forcefully converts both operands to the same value before
comparing, `===` only returns true if both operands are of the same type and
equal.

## 17

The function returns the array `[2, 4, 6]`. The `doSomething` function
multiplies a number by 2. When the array `[1, 2, 3]` and the function 
`doSomething`is passed into the `modifyArray` function, it calls `doSomething`
on every element of `[1, 2, 3]`, appends every modified element to a new array,
and returns the result, leading to a new array where every element is the 
corresponding element in `[1, 2, 3]` multiplied by 2.

## 19

The output of the code is:

1
4
3
2