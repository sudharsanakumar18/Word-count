# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open file in read mode.
### Step 2: 
Read the text using read funcion.
### Step 3: 
Split the text using space separator.
### Step 4:  
The length of the split list should be equal to the number of words in the text file.
### Step 5: 
Now give print().
### Step 6: 
End the program.

## PROGRAM:
```
Developed by: Sudharsana kumar S R
Ref.No: 23007374
num=0
with open("file1.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:
![python exp 5a](https://github.com/sudharsanakumar18/Word-count/assets/138849110/36a112ee-af50-4e2e-8017-2c62705b1996)

## RESULT:
Thus the program is written to find the word count from a text.
