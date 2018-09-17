# Algorithms and Data Structures

## Deque
### Description  
(usually pronounced like "deck") is an irregular acronym of double-ended queue. Double-ended queues are sequence containers with dynamic sizes that can be expanded or contracted on both ends (either its front or its back).

### Programming Notes
I used python build-in list as the Data Structure. The rear of the array is the first element while the front of the array is the last
element. I used the Pop Method to remove elements from front and rear of the array. Passing in a zero in the parameter while remove element from the rear of the array and passing in nothing will remove from the front of the array. To added element to the front of array by using the Append Method. The Insert Method is used to added the the rear of the array.  

### References
* [5.1 More on Lists](https://docs.python.org/3.1/tutorial/datastructures.html)

## Linked List

## List - Anagram (Checking Off)

### Description  

Checking Off - This method uses the first list to compares to the second list. When this program finds a match it sets the value it the second list to None.


### Programming Notes

I used the Python Built-in **Any** Function to check if the list contains all Nones. The Any Return True if any element of the iterable is true. If the iterable is empty, return False. 

### References

* [Any Method - Programiz](https://www.programiz.com/python-programming/methods/built-in/any)


## List - Anagram (Sort and Compare)

### Description

Sort and Compare - So, if we begin by sorting each string alphabetically, from a to z, we will end up with the same string if the original two strings are anagrams

### Programming notes

I used the Python Build-in **Sort** Function to alphabetical order the two lists before comparing the two lists together to see if they are the same.

### References

* [Sorting HOW TO](https://docs.python.org/3.3/howto/sorting.html)

## List - Anagram(Count and Compare)

### Description

First I initialize two arrays with all zeroes this will prepresent each letter in the alphabet.  Then I count the occuance of letter in both strings.  After counting the occurance of each letter I check to see if both string have the same number letter in each string. 

### Programming Notes

ord(c) - Given a string representing one Unicode character, return an integer representing the Unicode code point of that character. For example, ord('a') returns the integer 97 and ord('€') (Euro sign) returns 8364.

Sometimes we need to initialize a list in advance to  have a particular number of elements. 
[0]*26 = [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]
[0 for i in range(26)] =  [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]

Python 3 does not have cmp. If you really need the cmp() functionality, you could use the expression (a > b) - (a < b) as the equivalent for cmp(a,b).)








### References

## Nesting Dictionary

## Neting List

## Stack - Decimal to Binary Conversion

## Stack - Simple Balanced Parentheses

## Stack
