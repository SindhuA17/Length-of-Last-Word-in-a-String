# Length-of-Last-Word-in-a-String

Logic and algorithm :

1. Splitting input strings:

The input for the function lastword is a string s.
The split() method is used without any arguments to split the input string s into a list of words. This technique eliminates leading and trailing whitespaces and separates the string at spaces.
The list of words that is produced is kept in the variable word.

2. Look for a blank string

The function determines whether the word (word) list is empty. Cases where the input string is empty or contains only spaces are handled by this condition.
The method returns 0 if there are no words, meaning that there isn't a last word to measure.

3. Length of Return for Last Word:

The method returns the length of the last word in the list if there are any words in it. Negative indexing involves counting from the end, so to accomplish this, use words[-1] to access the last entry of the words list, and then len(words[-1]) to determine the word's length.

4. Gather User Data and Present Outcome:

Then, using input("Enter a string:"), the software requests input from the user.
Using the user's input, it calls the lastword function, storing the outcome in the response variable.
Lastly, print("Length:", response) is used to output the final word's length.
