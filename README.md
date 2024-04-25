# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python

# Program to mark the maximum of marks using the list method sort.
# Developed by : PRAKASH C
# Register No : 212223240122

def max_marks(array):
    return max (array)

```

ii)	# To find the maximum marks using the list method max().
```Python

# Program to find the maximum marks using the list method max().
# Developed by : PRAKASH C
# Register No : 212223240122

def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python

# Program to find the maximum marks without using builtin functions.
# Developed by : PRAKASH C
# Register No : 212223240122

def max_marks(marks):
    max_mark=0
    for i in marks:
        if i>max_mark:
            max_mark=i
    return max_mark

```



## Output:


i) # To find the maximum of marks using the list method sort.

![Screenshot 2024-04-25 064229](https://github.com/Prakash-Chandran/FindMaximum/assets/147120899/94b0a2e2-566c-4b96-b030-35eaed52cb2d)


ii) # To find the maximum marks using the list method max().

![Screenshot 2024-04-25 064246](https://github.com/Prakash-Chandran/FindMaximum/assets/147120899/35d879ae-9cb1-45b9-ba7d-1a741d2a5b7f)


iii) # To find the maximum marks without using builtin functions.

![Screenshot 2024-04-25 064300](https://github.com/Prakash-Chandran/FindMaximum/assets/147120899/a7073e57-37b5-4ff4-8ebd-2baf2cd44cca)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
