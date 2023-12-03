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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: PULI NAGA NEERAJ
RegisterNumber: 23004033
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
```
  


ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by:  PULI NAGA NEERAJ
RegisterNumber: 23004033
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large
```



iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: PULI NAGA NEERAJ
RegisterNumber: 23004033
''' 
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
```
  



## Sample Input and Output
![output](./img/max_marks1.jpg) 
![image](https://github.com/PuliNagaNeeraj/FindMaximum/assets/138849173/704a0980-1ccf-4de6-8fa0-5208fe10cfff)
![image](https://github.com/PuliNagaNeeraj/FindMaximum/assets/138849173/d2e08521-750c-4a2d-bd0a-9d1df89f2562)


## Output:
![image](https://github.com/PuliNagaNeeraj/FindMaximum/assets/138849173/74f4249c-f434-43e5-b3dc-ca70b655bbcf)
![image](https://github.com/PuliNagaNeeraj/FindMaximum/assets/138849173/969a80f0-80b2-47df-8c3c-e6065eb6fece)
![image](https://github.com/PuliNagaNeeraj/FindMaximum/assets/138849173/e9a86e96-fc6f-4ebb-ac85-65109a9e24e7)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
