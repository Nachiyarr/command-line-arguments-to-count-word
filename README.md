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
with open(sys.argv[1],'r') as f:
    for line in f:
        word=line.split()
        count += len(word)
print("Word Count in file =",count)
```

### OUTPUT:
![zia py](https://user-images.githubusercontent.com/113497340/195771530-980010be-d6fd-45b3-ba0b-06578d352b4f.png)


![Screenshot from 2022-10-14 11-15-56](https://user-images.githubusercontent.com/113497340/195771838-612bf3d1-088a-45c6-986e-a2e497b51215.png)






## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
