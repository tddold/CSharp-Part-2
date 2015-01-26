Homework: Methods
=================

### Problem 1.
*	Write a method that asks the user for his name and prints `“Hello, <name>”`
*	Write a program to test this method.

_Example:_

| input |     output    |
|:-----:|:-------------:|
| Peter | Hello, Peter! |

### Problem 2.
*	Write a method `GetMax()` with two parameters that returns the bigger of two integers.
*	Write a program that reads `3` integers from the console and prints the biggest of them using the method `GetMax()`.

### Problem 3.
*	Write a method that returns the last digit of given integer as an English word.

_Examples:_

| input | output |
|:-----:|:------:|
| 512   | two    |
| 1024  | four   |
| 12309 | nine   |

### Problem 4.
*	Write a method that counts how many times given number appears in given array.
*	Write a test program to check if the method is workings correctly.

### Problem 5.
*	Write a method that checks if the element at given position in given array of integers is bigger than its two neighbours (when such exist).

### Problem 6.
*	Write a method that returns the index of the first element in array that is bigger than its neighbours, or `-1`, if there’s no such element.
*	Use the method from the previous exercise.

### Problem 7.
*	Write a method that reverses the digits of given decimal number.

_Example:_

| input | output |
|:-----:|:------:|
| 256   | 652    |

### Problem 8.
*	Write a method that adds two positive integer numbers represented as arrays of digits (each array element `arr[i]` contains a digit; the last digit is kept in `arr[0]`).
*	Each of the numbers that will be added could have up to `10 000` digits.

### Problem 9.
*	Write a method that return the maximal element in a portion of array of integers starting at given index.
*	Using it write another method that sorts an array in ascending / descending order.

### Problem 10.
*	Write a program to calculate `n!` for each `n` in the range [`1..100`].

_Hint: Implement first a method that multiplies a number represented as array of digits by given integer number._

### Problem 11.
*	Write a method that adds two polynomials.
*	Represent them as arrays of their coefficients.

_Example:_

x<sup>2</sup> + 5 = `1`x<sup>2</sup> + `0`x + `5`	=>	{`5`, `0`, `1`}

### Problem 12.
*	Extend the previous program to support also subtraction and multiplication of polynomials.

### Problem 13.
*	Write a program that can solve these tasks:
	*	Reverses the digits of a number
	*	Calculates the average of a sequence of integers
	*	Solves a linear equation `a * x + b = 0`
*	Create appropriate methods.
*	Provide a simple text-based menu for the user to choose which task to solve.
*	Validate the input data:
	*	The decimal number should be non-negative
	*	The sequence should not be empty
	*	`a` should not be equal to `0`

### Problem 14.
*	Write methods to calculate `minimum`, `maximum`, `average`, `sum` and `product` of given set of integer numbers.
*	Use variable number of arguments.

### Problem 15.*
*	Modify your last program and try to make it work for any number type, not just integer (e.g. decimal, float, byte, etc.)
*	Use generic method (read in Internet about generic methods in C#).
