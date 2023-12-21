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

# Program to mark the maximum of marks using the list method sort
# Developed by: ARUNMOZHI VARMAN T
# RegisterNumber: 23002304
```
def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().

# Program to find the maximum marks using the list method max().
# Developed by: ARUNMOZHI VARMAN T
# RegisterNumber: 23002304
```
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.

# Program to the maximum marks without using builtin functions.
# Developed by: ARUNMOZHI VARMAN T
# RegisterNumber: 23002304
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```

## Output:
Program to mark the maximum of marks using the list method sort
![Screenshot 2023-12-21 233043](https://github.com/ArunmozhiVarmanT/FindMaximum/assets/144870523/e215d719-99b0-48f6-9e8d-b77115927c56)

 Program to find the maximum marks using the list method max().
 ![Screenshot 2023-12-21 233114](https://github.com/ArunmozhiVarmanT/FindMaximum/assets/144870523/8d2f7303-a57f-4a2c-80b8-9370614dabe6)

 Program to the maximum marks without using builtin functions.
 ![Screenshot 2023-12-21 233141](https://github.com/ArunmozhiVarmanT/FindMaximum/assets/144870523/143a41a3-81f5-499a-9bae-eaebdcc3a18b)





## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
