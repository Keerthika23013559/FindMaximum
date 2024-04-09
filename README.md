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
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
#program to find the maximum mark using list method max
#Developed by : Keerthika M P
#Register number : 212223240071

def max_marks(marks):
    return max(marks)



```

iii) # To find the maximum marks without using builtin functions.
```Python
#program to find the maximum mark without using built in function
#Developed by : KEERTHIKA M P
#Register number : 212223240071

def max_marks(marks):
    max_mark = marks[0]
    for i in marks:
        if i > max_mark:
            max_mark = i
    return max_mark



```



## Output:
PROGRAM 1
![Screenshot 2024-04-09 141102](https://github.com/Keerthika23013559/FindMaximum/assets/162658262/b871dbd0-33e4-4b27-9a1a-136689a92d47)

PROGRAM 2
![Screenshot 2024-04-09 141052](https://github.com/Keerthika23013559/FindMaximum/assets/162658262/523ca2a5-7a9d-43b9-b35c-05cbf0addeb6)

PROGRAM 3
![Screenshot 2024-04-09 141040](https://github.com/Keerthika23013559/FindMaximum/assets/162658262/334260cc-5023-49a9-ade9-76d738e0b444)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
