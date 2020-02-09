# Secondstring

**Simple program that asks a user to input a string and outputs every second character in reverse order**

*Week 3 Programming & Scripting Task*

Program Overview:
- Program prompts user to input a string
- Program uses slice notation to output every second character in reverse order.
- Slice notation string\[*'start'*:*'end'*:*'step'*]
```
string[::-2]
```
  - using negative 2 for *'step'* & leaving *'start'*
& *'end'* blank will count backwards from the end until the beginning of the inputted string in increments of 2

Example of input & output of Program:
```
secondstring.py
Enter String: the quick brown fox jumps over the lazy dog.
.o zletrv pu o wr cu h
```

Reference:
[Reverse String Slicing](https://stackoverflow.com/questions/21617586/reverse-string-string-1-works-but-string0-1-and-others-dont)

> Beginning with the character at **start**, increment by **step** until (but not including) **end**

