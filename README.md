## 1. str.islower(): is a string method that converts a given vareable to lower case
# example;
name = "PYTHON"
print(name.lower())

## 2. str.isupper(): is a string method that converts a given vareable to upper case
# example;
name = "lets do it"
is_upper = name.upper()
print(is_upper)

## 3. str.title(): is a string method that converts a given vareable to title
# example;
me = "strong"
print(me.title()) # i expect it to print   Strong.


## str_capitalize : is a string method that converts a given string first letter to capital letter
# example:-
name = "i am a geek"
print(name.capitalize()) # this will print "I am a geek"

## str_swapcase: is a string method that converts a given string to capital if it was small and vise versa
example:- 
name = "habTAMu .g"
print(name.swapcase()) # this will print HABtamU .G

## str_find(): is a string method that finds the smallest index from a given substring
# example:-
name = "you look so much better when u smile"
print(name.find("much")) # this will print 10 

## str_endswith: it is a string method that used to check if  the sub string is the end of the string
# example :-
name = "yeabsera sisay"
print(name.endswith("yeabsera")) # i expect this to print false because yeabsera is the start not the end

## str_starswith: it is a string method that used to check if  the sub string is the start of the string
# example :-
name = "i'm learning python"
print(name.starswith("i'm")) # i expect this to print true because i'm is the start of the string

## str_index: string method that used to find the smallest index in a sub string
# example :-
name = "yishak is lazy"
print(name.index("lazy")) # i expect this to print 9 because a is the smallest index in the sub string

## str.count(): it is a string method that counts the number of occurances in a substring and string
# example:-
name = "apple"
print(name.count("p")) # i expect this to print 2 because p occured 2 times in the string

## str.replace(): it is a string method that replaces all occurrences of a substring with another substring
# example:-
name = "my name"
print(name.replace("my","his")) # i expect this to print "his name" by replacing my by his

## str.strip(): it is a string method that removes leading and trailing whitespace
# example:-
name = " hello measter "
<<<<<<< HEAD
print(name.strip()) # i expect it to print "hellow measter" by removing the whitespaces
=======
print(name.strip()) # i expect it to print "hellow measter" by removing the whitespaces
## str.join:  Joins elements of an iterable (e.g., list) into a single string using the string as a separator.
# example:- 
name = "me","i"
print(" and ".join(name)) #this will print "me and i"

## str.isalpha:  Checks if all characters in the string are alphabetic (letters)
# example:- 
name = "bc23"
print(name.isalpha()) # this will print false because there are caracters other than alphabets on the string

## str.isspace():- Checks if all characters in the string are whitespace.
# example :-
name = " "
print(name.isspace()) #this will print true because the string cosistes space only

## str.isalnum():- Checks if all characters in the string are alphanumeric (letters or digits).
# example :-
name = "me123"
print(name.isalnum()) # this will print true because the string cosistes number and alphabetes only

## str.format():- Formats the string by replacing placeholders  {}  with specified values.
# example:-
name = "hi {}"
print(name.format("mr")) # this will print "hi mr" by formating {} and replacing it by "mr"


## str.digit():-  Checks if all characters in the string are digit
# example :-
name = "1234"
print(name.isdigit()) # this will print true because the string is consistes of digit only

## str.lower() :- Converts all characters in the string to lowercase.
# example:
name = "WHITE"
print(name.lower()) # this will print "white"

## str.upper():-Converts all characters in the string to uppercase
# example:
name = "black"
print(name.upper()) # this will print  "BLACK"

>>>>>>> 1aca5206b9c9258f562a12fe4fb54f6919427f51
