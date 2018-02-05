# 3-concat-and-arithmetic-functions

## Concatenating Strings in Python
A very powerful feature of strings is that they can be combined. When we join two or more strings into one, it is called concatenation.

We concatenate strings with a plus sign like this:
```
strVar = "Hello" + " " + "World"
```
Note that the string in the middle contains a "space" character 

We can concatenate string variables the same way:
```
str1 = "Hello "
str2 = World"
strVal = str1 + str2
```
These are interchangeable:
```
str1 = "Hello"
strVal = str1 + " World"
```

It is not possible to concatenate variables of different types. To get one string that can be printed, you must convert the number type into a string like this:
```
intvar = 10
strVar = "Number of memes today: " + str( intVar )
```

## Arithmetic in Python
Simple math operations are possible with both variables and numbers. 

Adding:
```
sumVar = 1 + 2

num1 = 34
num2 = 5
sumVar = num1 + num2
```
Subtracting:
```
sumVar = 3 - 5

num1 = 9
num2 = 6
sumVar = num1 - num2 
```

Multiplying:
```
productVar = 2 * 2

num1 = 4
num2 = 5
productVar = num1 * num2
```
Dividing:
```
productVar = 10 / 2
num1 = 10
num2 = 6
productVar = num1 / num2
```

## Your Task
1.  Show how to concatenate several strings into one. Use `print()` to show the pieces and the final string. Bonus points for using `format()` in your final output.
2.  Create a HUGE calculation using different combinations of operators. Use `print()` to show each step. Bonus points for using `format()` in your final output.
3.  Write a word-problem that gets printed to the console. Then demonstrate it being solved by printing each step and doing the calculation. Don't forget to convert your integers into strings for combined output. Bonus points for using `format()` in your final output.
