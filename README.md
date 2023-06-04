# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module

### Step 2: 
Open the file with sys.argv[1]
 
### Step 3: 
Use the for loop to select the content in file

### Step 4:  
Use split function to to separate the file content into words or strings

### Step 5: 
Count the length of the words using len

### Step 6: 
Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: S.ROSELIN MARY JOVITA
RegisterNumber: 212222230122

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("no of words in a file",count)

```
    
### OUTPUT:

![command line arg1](https://github.com/Roselinjovita/command-line-arguments-to-count-word/assets/119104296/3bb513dd-6c10-4b23-927f-679d9232ef02)


![command line arg2](https://github.com/Roselinjovita/command-line-arguments-to-count-word/assets/119104296/fcfb3837-d41d-4f16-a7cb-cf0b1c68108d)


![command line arg3](https://github.com/Roselinjovita/command-line-arguments-to-count-word/assets/119104296/5ed5b05c-a05a-4ac5-984d-468b389db7d2)

 



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
