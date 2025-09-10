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
<img width="768" height="179" alt="image" src="https://github.com/user-attachments/assets/1de7ea7d-cf74-4d37-b311-fde311a56fe6" />

## How i made it
For the Alphabet Soup Problem, I first created na function that turns the string into a list of elements of letters using the "list()" command and arranged the list into an alphabetical order using the "sort()" command. Lastly i used the the "join()" command in the function to turn the list of elements of letters back into a single string then the function will return the alphabetically ordered string

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
<img width="790" height="332" alt="image" src="https://github.com/user-attachments/assets/5e52416b-9852-439c-8beb-ef3b881293ba" />

## How i made it:
For the Emoticon Problem, I created a function which has an if-else conditional statement in which checks first if the statement has the specific words to turn into an emoticon using the said conditional statement "if" and "elif" then if that sentence has that specific word, it will replace the word with the emoticon using the replace command.If the sentence dont have the specific words to turn into an emoticon, it will pass through the fucntion without changing anything using the "else" function on the last line of the condition. the function will end with the sentence returning with or without changes to it. 

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
<img width="1176" height="227" alt="image" src="https://github.com/user-attachments/assets/49fa214b-e2f1-41f3-a9bf-dbd7e64b3948" />

## How i made it
For the unpacking list problem, i first displayed the 1st element using the command "print(lst[0])", after that i stored the last element into a variable using the code "last = lst[-1]" since the negative index moves backward thus moving once backward results to the last element in the array.I then proceeded to delete the first and the last element using the "del()" code so that the element that will be left is the middle elements. With this i displayed the whole array since the only thing left is the middle elements and proccedded to print the last element that is stored in a variable.

## Output
<img width="121" height="47" alt="image" src="https://github.com/user-attachments/assets/36c53a4b-2ebf-4452-9257-d929ad38d76d" />

## Lesson learned
Through solving this problem, i now understand the concept of index of the array since for this problem i had to use a negative value of an index in which moves the index backward. Through this problem, i managed to critically think about the problem since i noticed i can delete the first and last element leaving only the middle elements but i needed to store the value of the last element before i delete it so that i can display the last element when needed.
