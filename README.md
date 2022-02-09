# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:

### Step 1:
Assign a variable for value zero

### Step 2:
open then required file by using the function "with"

### Step 3:
Then use the for loop for assigning the i value in the file

### Step 4:
using split function to split the words

### Step 5:
Finding the length of the words by using len() function

### Step 6:
Calling the function and printing the number of words.
## PROGRAM:
```
with open("word_text.txt","r")as fp:
    count=0
    for data in fp:
        x=data.split()
        for i in x:
            count+=1
        print("Number of words : ",count)
```

### OUTPUT:

![output1](./op1.jpg)

![output2](./op2.jpg)


## RESULT:
Thus the program is written to find the word count from a text.
