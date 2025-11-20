Exp.No:3a
STRING - FIND AND REPLACE
AIM
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

ALGORITHM
Begin the program.
Input the original string str1 and the word to be replaced replace_str.
Ask the user to input the new replacement word str2.
Use the replace() method in Python to replace all occurrences of replace_str in str1 with str2.
Store the modified string in str3.
Display the original string (str1) and the modified string (str3).
Terminate the program.
PROGRAM
Reg no:212223070012 Name:Lithick Kumar M N

def replace_word_in_string():
    original_string = input("Enter the original string: ")
    word_to_replace = input("Enter the word to replace: ")
    new_word = input("Enter the new word: ")
    updated_string = original_string.replace(word_to_replace, new_word)
    print("Updated string:", updated_string)

replace_word_in_string()

OUTPUT

<img width="827" height="114" alt="image" src="https://github.com/user-attachments/assets/5a4c1529-ac79-4362-90af-73a67506d827" />


RESULT
Thus the program is executed successfully
