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
Developed by: MANOJ G
RegisterNumber: 212222240060
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: MANOJ G
RegisterNumber: 212222240060
'''
def max_marks(marks):
    return max(marks)



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: MANOJ G
RegisterNumber: 212222240060
'''
def max_marks(list1):
    l=list1[0]
    for i in list1:
        if i>l:
            l=i
    return l        




```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![243061645-a817b144-140e-4fc2-91a9-8962fc4ce867](https://github.com/Danielmanoj/FindMaximum/assets/69635071/da33c2a4-e5ea-4b24-94f9-319c5e8804a5)


## Output:
i) # To find the maximum of marks using the list method sort. 
![243061652-377ee5b6-09a8-4d64-a864-9d4b78158c25](https://github.com/Danielmanoj/FindMaximum/assets/69635071/25eb7058-357d-47b4-b3fa-d8ba8c3f7379)
ii) # To find the maximum marks using the list method max(). 
![243061657-9c3ff0e9-7104-4ffb-b906-50c2a775c2d7](https://github.com/Danielmanoj/FindMaximum/assets/69635071/eacc435b-e98b-43fd-9ad1-aa2463cf9ac2)
iii) # To find the maximum marks without using builtin functions. 
![243061664-0628c1d1-9e9d-4a48-b4a9-c2fdcae625ad](https://github.com/Danielmanoj/FindMaximum/assets/69635071/64c5c595-8af6-497d-a868-10a12c71a542)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
