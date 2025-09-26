# Programming_Assignment_1
This Programming Assignment contains the python code solution to the Alphabet soup, Emoticon and Unpacking list problems made by Adrian S. De Guzman from 2 ECE - A, as a assigment for his course ECE 2112 - Advanced Computer Programming and Algorithms
___
# Alphabet Soup Problem

## Overview
We are tasked to create a function that takes a string and returns a string with its letters
in alphabetical order.
Examples include: alphabet_soup(“hello”) ➞ ehllo
                  alphabet_soup(“hacker”) ➞ acehkr
## Code
```python
def alphabet_soup(s):
    ordered = list(s) 
    ordered.sort() 
    ordered = ''.join(ordered) 
    return ordered
print(alphabet_soup("hello"))
```
## How i made it
```python
def alphabet_soup(s): #creates a function named alphabet_soup
    ordered = list(s) #turn the string into list of letters
    ordered.sort() #sort the letters
    ordered = ''.join(ordered) #join the letters into a single string
    return ordered
print(alphabet_soup("hello")) #prints the backwarded string
```
## Output
<img width="93" height="49" alt="image" src="https://github.com/user-attachments/assets/9ec28b90-d799-41c6-99f0-c6ecfbbd0492" />

## Lesson learned
Trough solving this problem, i began to understand the codes of python, since this is my first problem in coded using python, i learned the basic manipulation of a list and string like turning a string into a list of element and sotring a list alphabetically then turning it back into another string. With this problem, i began to grasp the concept of python codes.

___
# Emoticon Problem

## Overview
We are tasked to create a function that changes specific words into emoticons. Given a sentence
as a string, replace the words smile, grin, sad and mad with their corresponding emoticon:

<img width="253" height="161" alt="image" src="https://github.com/user-attachments/assets/b14c0a16-b9b0-457b-91b1-8a3c7158ee9c" />

## Code
```python
def emotify(emotion): 
    if "smile" in emotion: 
        return emotion.replace("smile",":)") 
    elif "grin" in emotion:
        return emotion.replace("grin",":D")
    elif "sad" in emotion:
        return emotion.replace("sad",":((") 
    elif "mad" in emotion:
        return emotion.replace("mad",">:(")
    else:
        return emotion 
print(emotify("Make me smile")) 
```
## How i made it:
```python
def emotify(emotion): #creates a funcion named emotify
    if "smile" in emotion: 
        return emotion.replace("smile",":)") #looks for string "smile" and replaces it
    elif "grin" in emotion:
        return emotion.replace("grin",":D") #looks for string "grin"  and replaces it
    elif "sad" in emotion:
        return emotion.replace("sad",":((") #looks string "sad" and replaces it
    elif "mad" in emotion:
        return emotion.replace("mad",">:(") #looks for string "mad" and replaces it
    else:
        return emotion #dont replace anything if there are no emoticons
print(emotify("Make me smile")) #prints the set of string with the changed value of the specific string
```
## Output
<img width="138" height="41" alt="image" src="https://github.com/user-attachments/assets/c205b52d-e533-49b9-8d1c-747fc886f28d" />

## Lesson learned
With this problem, i now understnad the concept of conditional statements with is an essential part of programming. Through creating a set of code that checks if a sentence as a specific word, i now know that i can manipulate a string then change a specific string into another specific string. 

___
# Unpacking List Problem

## Overview
We are tasked to unpack the list writeyourcodehere into three variables, being first,
middle, and last, with middle being everything in between the first and last element. Then print all three

## Code
```python
lst = [1,2,3,4,5,6]
print("first:",lst[0]) #get the first element of the list and replace
last = lst[-1] #get the last element of the list
del(lst[0])
del(lst[-1]) #delete the first and last element of the list so that the only ones left is the middle list
print("middle:",lst)
print("last:",last)
## How i made it
For the unpacking list problem, i first displayed the 1st element using the command "print(lst[0])", after that i stored the last element into a variable using the code "last = lst[-1]" since the negative index moves backward thus moving once backward results to the last element in the array.I then proceeded to delete the first and the last element using the "del()" code so that the element that will be left is the middle elements. With this i displayed the whole array since the only thing left is the middle elements and proccedded to print the last element that is stored in a variable.
```
## How does it work
```python
lst = [1,2,3,4,5,6] #creates the list with the given values
print("first:",lst[0]) #gets the first element of the list and replace
last = lst[-1] #get the last element of the list and stores it into a variable for later uses
del(lst[0]) #deletes the first element of the list
del(lst[-1]) #delete the last element of the list so that the only ones left is the middle list
print("middle:",lst) #prints the middle values
print("last:",last) #prints the last value of the list that was stored in a variable earlier
```
## Output
<img width="121" height="47" alt="image" src="https://github.com/user-attachments/assets/36c53a4b-2ebf-4452-9257-d929ad38d76d" />

## Lesson learned
Through solving this problem, i now understand the concept of index of the array since for this problem i had to use a negative value of an index in which moves the index backward. Through this problem, i managed to critically think about the problem since i noticed i can delete the first and last element leaving only the middle elements but i needed to store the value of the last element before i delete it so that i can display the last element when needed.
___
## Version 3
