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
```
i)	# To find the maximum of marks using the list method sort.

def max_marks(list1):
    max=list[0]
    for num in list1:
        if(num>max):
            max=num
    return max

ii)	# To find the maximum marks using the list method max().

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
iii) # To find the maximum marks without using builtin functions.
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```













## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# To find the maximum of marks using the list method sort.
![output](./maximum1.png)

ii)	# To find the maximum marks using the list method max().
![output](./maximum2.png)

iii) # To find the maximum marks without using builtin functions.
![output](./maximum3.png)








## Result:

Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
