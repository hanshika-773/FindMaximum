# Date: 
# Ex.No 6: Find the maximum of a list of numbers
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
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max_mark = marks[0]
    for mark in marks:
        if mark > max_mark:
            max_mark = mark
    return max_mark

```



## Output:
![Screenshot 2024-10-16 163700](https://github.com/user-attachments/assets/03272fe5-3c7c-4f31-8aea-7645feb2beb0)
![Screenshot 2024-10-16 163711](https://github.com/user-attachments/assets/e6227345-3a1c-43b9-9324-10a6db57095c)
![Screenshot 2024-10-16 163722](https://github.com/user-attachments/assets/fa35e1ba-8d5b-4b78-b81c-db3744dfc2f9)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
