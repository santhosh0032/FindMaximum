# EX06 Find the maximum of a list of numbers
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
MAXIMUM MARKS USING LIST METHOD SORT()
DEVELOPED BY: K Santhosh
REGISTER NUMBER: 212224050041

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
MAXIMUM MARKS USING LIST METHOD MAX()
DEVELOPED BY: K Santhosh
REGISTER NUMBER: 212224050041

def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
MAXIMUM MARKS WITHOUT USING BUILTIN FUNCTIONS
DEVELOPED BY: K Santhosh
REGISTER NUMBER: 212225040041

def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark
```



## Output:

i)	# To find the maximum of marks using the list method sort.
<img width="1847" height="1033" alt="image" src="https://github.com/user-attachments/assets/246629d1-668b-4d6c-b84a-cb081a2d0c14" />


ii)	# To find the maximum marks using the list method max().
<img width="1620" height="993" alt="image" src="https://github.com/user-attachments/assets/08dd8a4d-e64a-4dac-b7e9-49cdbc11cb4c" />


iii) # To find the maximum marks without using builtin functions.
<img width="1619" height="996" alt="image" src="https://github.com/user-attachments/assets/e86cfb51-81c5-46ab-b0b3-5641f6ac4a21" />


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
