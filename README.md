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
def max_marks(lst):
    lst.sort()
    MAX=lst[-1]
    return MAX


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max_num=list1[0]
    for i in list1:
        if i>max_num:
            max_num=i
    return max_num




```



## Output:
![image](https://github.com/sriharan23000516/FindMaximum/assets/139841769/031e8a60-65bf-4587-8a27-7a5b91faf69d)

![image](https://github.com/sriharan23000516/FindMaximum/assets/139841769/cc5f9d04-568a-47bf-8833-89a60f068260)

![image](https://github.com/sriharan23000516/FindMaximum/assets/139841769/4603afc7-0d55-4aac-beb3-62ac8e487974)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
