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
Developed by: Senthil Kumar S
RegisterNumber: 21500410    
'''
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Senthil Kumar S
RegisterNumber: 21500410
'''
def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Senthil Kumar S
RegisterNumber: 21500410
'''
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![sort](https://user-images.githubusercontent.com/93860256/148635007-641c9b18-02a6-43e1-9132-ba447cc21646.PNG)
![max](https://user-images.githubusercontent.com/93860256/148635030-9dd4d0a6-d17d-4140-ae8c-a19adcb6cfa3.PNG)
![functions](https://user-images.githubusercontent.com/93860256/148635035-debeadd2-0d20-43ff-92e5-63fc209c64e3.PNG)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.