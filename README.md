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
```
Program to mark the maximum of marks using the list method sort
Developed by: Azeez Ahamad
RegisterNumber: 23003977
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
Program to mark the maximum of marks using the list method sort
Developed by: Azeez Ahamad
RegisterNumber: 23003977
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by:Azeez Ahamad
RegisterNumber: 23003977
def max_marks(marks):
    large=max(marks)
    return large
```
## Output:
### i)
![image](https://github.com/AzeezBT/FindMaximum/assets/150319523/669af766-c3ce-4e3e-b2d9-81bc7062a936)
### ii)
![image](https://github.com/AzeezBT/FindMaximum/assets/150319523/b6b2aa42-6b81-44be-a5fd-8f0b343b60cb)
### iii)
![image](https://github.com/AzeezBT/FindMaximum/assets/150319523/6769965e-eb63-4bc6-8564-707a5ebbf96d)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
