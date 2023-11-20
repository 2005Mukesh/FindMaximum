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
    return(max(marks))
```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for x in list1:
        if x > max:
            max = x
    return max        
```
## Output:
i)	# To find the maximum of marks using the list method sort.
![Screenshot 2023-11-20 135157](https://github.com/2005Mukesh/FindMaximum/assets/138849308/f53c7178-6fe6-4274-a168-70ee863d3a76)

ii)	# To find the maximum marks using the list method max().
![Screenshot 2023-11-20 135211](https://github.com/2005Mukesh/FindMaximum/assets/138849308/e05976af-69ff-41c5-a8ff-d67d0afeba19)

iii) # To find the maximum marks without using builtin functions.
![Screenshot 2023-11-20 135223](https://github.com/2005Mukesh/FindMaximum/assets/138849308/f41564b7-b413-484e-988a-768049251258)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
