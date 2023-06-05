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
    # write your code here
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    # write your code here
    max = list1[0]   
    for i in list1:
       if i > max:
        max = i
    return max


```
## Sample Input and Output

 

## Output:
![output]!![Screenshot (58)](https://github.com/Dineshsekhar2004/FindMaximum/assets/119405916/16991fd3-7ea0-46f6-a535-9552d94888c1)
![output]!![Screenshot (62)](https://github.com/Dineshsekhar2004/FindMaximum/assets/119405916/614dd097-3a87-4016-86ec-46a91413c2cc)
![output]![Screenshot (60)](https://github.com/Dineshsekhar2004/FindMaximum/assets/119405916/2d507bee-e379-4578-9de8-b286a612b70b)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
