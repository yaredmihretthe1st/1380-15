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