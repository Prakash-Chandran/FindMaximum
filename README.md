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

![Screenshot 2024-05-08 092836](https://github.com/Prakash-Chandran/FindMaximum/assets/147120899/2cb803b0-b422-44d8-8d87-7dd93f71b28b)


ii) # To find the maximum marks using the list method max().

![Screenshot 2024-05-08 092855](https://github.com/Prakash-Chandran/FindMaximum/assets/147120899/e768f80a-0b03-48c3-9a35-a8e9cae167de)



iii) # To find the maximum marks without using builtin functions.

![Screenshot 2024-05-08 092917](https://github.com/Prakash-Chandran/FindMaximum/assets/147120899/8d75d5de-8f4d-4d45-9946-2e00473bc695)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
