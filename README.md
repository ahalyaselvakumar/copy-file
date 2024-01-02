# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np

### Step 2: 
Enter the input values
 
### Step 3: 
Write python program for copying the contents from one file to naother file

### Step 4: 
Run the program 

### Step 5: 
Give the input file name

### Step 6: 
End the program

## PROGRAM:
```
'''
#program to copy the contents from one file to another file 
#Developed by : AHALYA S
#Register number : 23002896
'''
def copy(fname,newfile):
    with open(fname,'r')as fp:
        with open(newfile,'w')as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter an existing file:")
newfile=input("Enter a name for new file:")
copy(fname,newfile)
```

### OUTPUT:
![OUTPUT](<Screenshot 2024-01-02 150559.png>)


## RESULT:
Thus the program is written to copy the contents from one file to another file.