# Word Count

## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENTS REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:
Create a new text file and add comment
### Step 2: 
Create a python file and add program
### Step 3: 
Open the text file in read mode
### Step 4:  
Using for loop find the length of words
### Step 5:
Print the number of words
### Step 6:
End the program

## PROGRAM:
```python
# Program to count number of words in a text file
# Developed by: Prajeeth K T
# Reg. No.: 22002267
num_words=0
with open('some.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words {}".format(num_words))
```

### OUTPUT:
![](word%20count.png)

## RESULT:
Thus the program is written to find the word count from a text.
