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
```Python
#Developed by: 212222230120
#RegisterNumber: ROHIT JAIN D
```
- To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

- To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    maxi=max(marks)
    return maxi
```

- To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./images/max_marks1.jpg)   
## Output:
![output](./images/output.png) 
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.