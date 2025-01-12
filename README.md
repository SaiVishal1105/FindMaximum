# Find the maximum of a list of numbers
NAME: SAI VISHAL D<BR>
REG.NO: 212223230180
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
Developed by: Sai Vishal D
RegisterNumber: 23013576
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Sai Vishal D
RegisterNumber: 23013576
'''
def max_marks(marks):
    m=max(marks)
    return m



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Sai Vishal D
RegisterNumber: 23013576
'''
def max_marks(marks):
    m=max(marks)
    return m


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![Alt text](<Screenshot 2023-11-26 154633.png>)
![Alt text](<Screenshot 2023-11-26 154729.png>)
![Alt text](<Screenshot 2023-11-26 155020.png>)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
