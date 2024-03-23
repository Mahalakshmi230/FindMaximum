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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    maximum=marks[0]
    for i in marks:
        if(i>maximum):
            maximum=i
    return maximum 
```



## Output:

![Screenshot 2024-03-23 232859](https://github.com/Mahalakshmi230/FindMaximum/assets/149365324/f2b7dd09-e976-48f0-a2aa-fde1a071bcf8)
![Screenshot 2024-03-23 232918](https://github.com/Mahalakshmi230/FindMaximum/assets/149365324/f4f79d62-2a15-40d1-8f60-59cb0d6a6d46)
![Screenshot 2024-03-23 232931](https://github.com/Mahalakshmi230/FindMaximum/assets/149365324/45392ce2-f045-4807-8e06-9a02ea443d1f)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
