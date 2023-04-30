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
Developed by: KEERTHI VASAN A
RegisterNumber: 212222240048
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
  
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: KEERTHI VASAN A
RegisterNumber: 212222240048
'''
def max_marks(marks):
    large=max(marks)
    return large
    
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: KEERTHI VASAN A
RegisterNumber: 212222240048
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max=i
    return max
 
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot (139)](https://user-images.githubusercontent.com/107488929/235335836-43478e43-0c5b-4599-8e63-703a0692c668.png)
![Screenshot (140)](https://user-images.githubusercontent.com/107488929/235335912-365816f4-3164-4879-aa13-123aa0f603a4.png)
![Screenshot (141)](https://user-images.githubusercontent.com/107488929/235335935-23710300-be36-4bb7-b2c7-d026cc6023c0.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
