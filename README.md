#  Accept Three Digits and Print all Possible Combinations from the Digits:
## This is a Python Program to accept three distinct digits and print all possible combinations from the digits.

## Problem Description:
### It takes three distinct numbers and prints all possible combinations from the digits.

## Problem Solution:
- Take in the first, second and third number and store it in separate variables.
- Then append all the three numbers to the list.
- Use three for loops and print the digits in the list if none of their indexes are equal to each other.
- Exit.

## Append Method:
### append() method in python adds a single item to the existing list. It doesn't return a new list of items but will modify the original list by adding the item to the end of the list.

## Program Explanation:
- User must enter the first, second and third number.
- All the elements are appending into a list for the ease of comparison.
- The for loops range from 0-2 which are basically the indexes of the three elements in the list.
- If none of the indexes are equal to each other, the element associated with the particular element in the list is printed.
