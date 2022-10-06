# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2: 
Open file using commandline arguments.
 
### Step 3: 
Using for loop find the word count from the contents of a file.

### Step 4:
Use len to count number of words.

### Step 5: 
Give print statement.
### Step 6: 
End the program.

## PROGRAM:
#Developed by:Alagu Nachiyar K

#Registration no:22002084
```
import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word=line.split()
        count += len(word)
print("Word Count in file =",count)
```

### OUTPUT:
![countt](https://user-images.githubusercontent.com/113497340/194223146-2a8c4005-ddd2-427c-a28d-f9b5c10e176d.png)

![zia file](https://user-images.githubusercontent.com/113497340/194223216-a8af6726-081f-4fb3-a4ee-6719d43ad92f.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
