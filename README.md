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
''' 
Program to mark the maximum of marks using the list method sort
Developed by:DHARANYA.N
RegisterNumber:23006980
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by:DHARANYA.N
RegisterNumber: 23006980
'''
def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by:DHARANYA.N
RegisterNumber: 23006980
'''
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a



```
## Output:
i)
![image](https://github.com/Dharanya2005/FindMaximum/assets/145742468/b54b3008-59f2-4a11-90e7-ad89ac90d12b)

ii)
![image](https://github.com/Dharanya2005/FindMaximum/assets/145742468/38139d97-6664-4009-a65c-87a1a5a19873)

iii)
![image](https://github.com/Dharanya2005/FindMaximum/assets/145742468/2885625c-c6ec-4205-bf3e-83d3ee9b4d32)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
