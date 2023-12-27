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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: DHARSHAN PT
RegisterNumber: 23005803
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    a=max(marks)
    return a

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a

```

## Output:
![Screenshot 2023-12-27 225755](https://github.com/dharshanpt/FindMaximum/assets/138849376/10197aa2-57ce-4f52-960f-7619c51f18fa)
![Screenshot 2023-12-27 225842](https://github.com/dharshanpt/FindMaximum/assets/138849376/9c2742ac-4254-4566-91ac-4f650006d4e3)
![Screenshot 2023-12-27 225859](https://github.com/dharshanpt/FindMaximum/assets/138849376/51076417-2800-413f-9fc6-4a41c642d7c3)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
