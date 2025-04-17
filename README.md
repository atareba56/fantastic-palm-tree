# fantastic-palm-tree
Answers to Questions
Question 1

base = "Programming"
reverse_base = base[: : -1]
print(f"Reverse Base of {base} : {reverse_base} ")

Question 2

name = input("Enter your name : ")
name_parts = name.split()
initials = ' '
for part in name_parts:
	initials += part[0].upper() + " . "
	print(f" {initials [: -1]}" )

Question 3

def is_palindrome(text):
    text = text.lower()
    return text == text[::-1]
string2 = input("Enter a string to check for palindrome: ")
if is_palindrome(string2):
    print(f"'{string2}' is a palindrome.")
else:
    print(f"'{string2}' is not a palindrome.")

Question 4

sentence = input("Enter a sentence: ")
word_count = len(sentence.split())
print(f"The sentence has {word_count} words.")

Question 5

string3 = "This is a string and it is an example."
modified_string = string3.replace("is", "was")
print(f"Modified string: {modified_string}")
