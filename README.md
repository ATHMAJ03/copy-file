# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from one file to another file.

### Step 2:
Using key word "with" to open the required file
 
### Step 3: 
Use for loop to get content from firstfile

### Step 4:  
use write function to write on secondfile

### Step 5: 
exit the program

## PROGRAM:
```
with open('f4.txt','r') as firstfile:
    with open('f5.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

### OUTPUT:
![copy](https://user-images.githubusercontent.com/118753139/214775972-fc4e8de3-0293-474c-99ff-ce68aa904c3e.png)
![f1](https://user-images.githubusercontent.com/118753139/214775997-2629c551-d15c-4814-a898-5142df3a3690.png)
![f2](https://user-images.githubusercontent.com/118753139/214776007-318fea0e-5e66-45d7-b22a-c2a6ca9ae3a8.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
