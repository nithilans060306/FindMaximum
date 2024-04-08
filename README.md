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
def max_marks(marks):
    marks.sort(reverse=True)
    return marks[0]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(a):
    return max(a)
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(a):
    m=a[0]
    for i in a:
        if(i>m):
            m=i
    return m
```
## Output:
### Using Inbuilt Sort Function:
![Exp6_1](image.png)
### Using Inbuilt Max Function:
![Exp6_2](image-2.png)
### Without Inbuilt Functions:
![EXp6_3](image-1.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
