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
Developed by: JAGADEESH P
RegisterNumber: 23013534
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
     

    


```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by: JAGADEESH P
RegisterNumber: 23013534
'''
def max_marks(marks):
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/jagadeesh9500/FindMaximum/assets/149087921/b59fb562-2b37-46fb-8419-56feb5b01fa3)
![image](https://github.com/jagadeesh9500/FindMaximum/assets/149087921/d83fad57-b353-4c36-b807-61e4d559383e)
![image](https://github.com/jagadeesh9500/FindMaximum/assets/149087921/b2a139f2-8606-44a1-82df-377ee94b23d0)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
