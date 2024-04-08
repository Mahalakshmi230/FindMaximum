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
![image](https://github.com/Mahalakshmi230/FindMaximum/assets/149365324/53fe7473-cab2-4ee9-a1c0-c7d5fa0154a3)
![image](https://github.com/Mahalakshmi230/FindMaximum/assets/149365324/2ff4f0aa-14d4-4a7b-8b0b-56bb395c3527)
![image](https://github.com/Mahalakshmi230/FindMaximum/assets/149365324/03b6576d-18c3-4a4d-845b-a11dbd06c200)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
