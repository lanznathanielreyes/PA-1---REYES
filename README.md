# ReyesLanzNathaniel-PA1
##### This is my submission for the Programming Assignment 1 | Introduction to Python Programming

##### Number 1:
The objective is to prompt the user to input any word and then create a code that sorts the letters in the word alphabetically. 
The first thing that I did was create an input syntax(n = input()) to allow the program to ask an input the moment it starts.
Basically, once the user typed any word, it will automatically be stored in the variable 'n'.
The syntax "result = alphabetize_string(n)" sorts the every character in the word aplhabetically, hence i addes it.
To show the output of the program, I made syntaxes that shows the original and sorted results.

##### Code 1:
def alphabetize_string(n):
    return ''.join(sorted(n))

n = input ("Enter a word: ")
result = alphabetize_string(n)
print ("Original: ",n)
print ("Sorted: ",result)

##### Number 2:
In this example, the task is to prompt user to input a sentence and allow emoticons to replace a specific strings that describes it.
The first thing I did was store the user's input inside variable 's' (s = input()). For every emoticon, I created a syntax that replaces it. (s=s.replace(emoticon,string))

##### Code 2:
s = input()
s=s.replace("smile",":)")
s=s.replace("grin",":D")
s=s.replace("sad",":((")
s=s.replace("mad",">:(")
print (s)

##### Number 3:
For the last problem, the task is to slice and display the array into its equivalent values. I initiated a variable containing an array with integers. 
After doing so, I assigned the position by dong this syntax, "first = (t[0])" until the last position. 
I used what I have learned about slicing that the first digit corresponds to the row and the next is for the column.
I printed the results one by one after assigning the syntaxes.

##### Code 3:
t = [1, 2, 3, 4, 5, 6]
first = (t[0])
middle = (t[1:5])
last = (t[5])
print("first:", first)
print("middle:", middle)
print("last:", last)


