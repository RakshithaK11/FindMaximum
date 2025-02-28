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
~~~
''' 
Program to mark the maximum of marks using the list method sort
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
~~~

ii)	# To find the maximum marks using the list method max().
~~~
''' 
Program to find the maximum marks using the list method max().
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    marks.sort()
    res=marks[-1]
    return res
~~~

iii) # To find the maximum marks without using builtin functions.
~~~
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
~~~
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![image](https://github.com/RakshithaK11/FindMaximum/assets/139336455/c07dc36f-6d70-4359-870c-dbc201cdc26e)
![image](https://github.com/RakshithaK11/FindMaximum/assets/139336455/9563e446-c030-443c-89f2-1e74e44f5128)



## Output:
![image](https://github.com/RakshithaK11/FindMaximum/assets/139336455/d55cdcc1-d1f3-40c4-b4cd-87fa1cd5dcd4)
![image](https://github.com/RakshithaK11/FindMaximum/assets/139336455/fca50fa6-e14f-495a-ab0b-fe8f9690007e)
![image](https://github.com/RakshithaK11/FindMaximum/assets/139336455/cdde46b9-4ab0-4c01-a570-10adcfdc151c)







## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
