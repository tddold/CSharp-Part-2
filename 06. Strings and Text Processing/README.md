Homework: Strings and Text Processing
=====================================

### Problem 1.
*	Describe the strings in C#.
*	What is typical for the string data type?
*	Describe the most important methods of the String class.

### Problem 2.
*	Write a program that reads a string, reverses it and prints the result at the console.

_Example:_

|  input | output |
|:------:|:------:|
| sample | elpmas |

### Problem 3.
*	Write a program to check if in a given expression the brackets are put correctly.

_Example of correct expression:_ `((a+b)/5-d)`.
_Example of incorrect expression:_ `)(a+b))`.

### Problem 4.
*	Write a program that finds how many times a sub-string is contained in a given text (perform case insensitive search).

_Example:_

The target sub-string is `in`

The text is as follows:
We are liv**in**g **in** an yellow submar**in**e. We don't have anyth**in**g else. **in**side the submar**in**e is very tight. So we are dr**in**k**in**g all the day. We will move out of it **in** 5 days.

The result is: `9`

### Problem 5.
*	You are given a text. Write a program that changes the text in all regions surrounded by the tags `<upcase>` and `</upcase>` to uppercase. The tags cannot be nested.

_Example:_ We are living in a <upcase>yellow submarine</upcase>. We don't have <upcase>anything</upcase> else.

_The expected result:_ We are living in a YELLOW SUBMARINE. We don't have ANYTHING else.

### Problem 6.
*	Write a program that reads from the console a string of maximum `20` characters. If the length of the string is less than `20`, the rest of the characters should be filled with `*`.
*	Print the result string into the console.

### Problem 7.
*	Write a program that encodes and decodes a string using given encryption key (cipher).
*	The key consists of a sequence of characters. 
*	The encoding/decoding is done by performing XOR (exclusive or) operation over the first letter of the string with the first of the key, the second – with the second, etc. When the last key character is reached, the next is the first.

### Problem 8.
*	Write a program that extracts from a given text all sentences containing given **word**.

_Example:_

_The word is:_ **in**

_The text is:_ We are living **in** a yellow submarine. We don't have anything else. Inside the submarine is very tight. So we are drinking all the day. We will move out of it **in** 5 days.

_The expected result is:_ We are living in a yellow submarine. We will move out of it in 5 days.

_Consider that the sentences are separated by `.` and the words – by **non-letter symbols**._

### Problem 9.
*	We are given a string containing a list of forbidden words and a text containing some of these words.
*	Write a program that replaces the forbidden words with asterisks.

_Example text:_ Microsoft announced its next generation PHP compiler today. It is based on .NET Framework 4.0 and is implemented as a dynamic language in CLR.

_Forbidden words:_ `PHP`, `CLR`, `Microsoft`

_The expected result:_ `********* announced its next generation *** compiler today. It is based on .NET Framework 4.0 and is implemented as a dynamic language in ***`.

