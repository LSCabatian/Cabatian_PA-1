# Cabatian_PA-1
1. Alphabet Soup Problem
``` python
def alphabet_soup(s):
    # Sort the characters in the string in alphabetical order.
    print ("". join(sorted(s)))                         
# Use the string to perform the function
alphabet_soup("hello")
alphabet_soup("hacker")

ehllo
acehkr
```

2. Emoticon Problen
``` python
def emotify(s):
    # Remove "smile" and replace with ":)" instead.
    s = s.replace ("Smile", ":)")
    # Remove "Grin" and replace with ":D" instead.
    s = s.replace ("Grin", ":D)")
    # Remove "Sad" and replace with ":((" instead.
    s = s.replace ("Sad", ":((")
    # Remove "Nad" and replace with "›:(" instead.
    s = s.replace ("Mad", ">:(")
    #Return the modified string with s.

Make me :)
I am >:(
```

3. Unpacking List Problem
``` python
def unpack_list(lst):
    # Open the first element.
    first = lst[0]
    # Open the middle element.
    middle = lst[1:-1]
    # Open the last element.
    last = lst[-1]
    # Print the output.
    print ("first: {},   middle: {},   last: {}". format(first, middle, last))

unpack_list (lst = [1, 2, 3, 4, 5, 6])

first: 1,   middle: [2, 3, 4, 5],   last: 6


