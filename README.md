# ReyesLanzNathaniel-PA1
##### This is my submission for the Programming Assignment 1 | Introduction to Python Programming

##### Number 1:
The objective is to prompt the user to input any word and then create a code that sorts the letters in the word alphabetically. 
The first thing that I did was create an input syntax(n = input()) to allow the program to ask an input the moment it starts.
Basically, once the user typed any word, it will automatically be stored in the variable 'n'.
The syntax "result = alphabetize_string(n)" sorts the every character in the word aplhabetically, hence i addes it.
To show the output of the program, I made syntaxes that shows the original and sorted results.

```Python
def alphabetize_string(n): # Defines a function that takes a string n.
    return ''.join(sorted(n)) # Sorts the letters of n and joins them back into a single string.

n = input("Enter a word: ") # Prompts the user to type a word and stores it in variable n.
result = alphabetize_string(n) # Calls the function to sort the letters and saves it in result.
print("Original: ", n) # Prints the original word the user typed.
print("Sorted: ", result) # Prints the sorted version of the word.

```
##### Number 2:
In this example, the task is to prompt user to input a sentence and allow emoticons to replace a specific strings that describes it.
The first thing I did was store the user's input inside variable 's' (s = input()). For every emoticon, I created a syntax that replaces it. (s=s.replace(emoticon,string))

```Python
s = input()  # Asks the user to type a sentence and stores it in s.
s = s.replace("smile", ":)")  # Replaces every "smile" in s with the smile emoticon.
s = s.replace("grin", ":D")  # Replaces every "grin" in s with the grin emoticon.
s = s.replace("sad", ":((")  # Replaces every "sad" in s with the sad emoticon.
s = s.replace("mad", ">:(")  # Replaces every "mad" in s with the mad emoticon.
print(s)  # Prints the new sentence with emoticons.

```

##### Number 3:
For the last problem, the task is to slice and display the array into its equivalent values. I initiated a variable containing an array with integers. 
After doing so, I assigned the position by dong this syntax, "first = (t[0])" until the last position. 
I used what I have learned about slicing that the first digit corresponds to the row and the next is for the column.
I printed the results one by one after assigning the syntaxes.

```Python
t = [1, 2, 3, 4, 5, 6]  # Creates a list named t with six numbers.
first = t[0]  # Takes the first number (index 0) from the list.
middle = t[1:5]  # Takes the numbers from index 1 up to (but not including) index 5.
last = t[5]  # Takes the last number at index 5.
print("first:", first)  # Prints the first number.
print("middle:", middle)  # Prints the middle numbers.
print("last:", last)  # Prints the last number.

```

