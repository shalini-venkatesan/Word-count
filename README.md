# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a new text file
### Step 2: 
Open the file using open() in read mode
### Step 3: 
Initialize count is 0
### Step 4:  
for each line split the words and store in a list
### Step 5: 
add the length of the list to the count for each line
### Step 6: 
print the count

## PROGRAM:
```py
##Program to count the words in a file
##developed by: Shalini V
##Register no: 22009257
fname = input('Enter file name: ')
num_words = 0
with open(fname, 'r') as f:
    for line in f:
        words = line.split()
        num_words += len(words)
print('Number of words: ',num_words)
```

### OUTPUT:
![out](/12.png)
## RESULT:
Thus the program is written to find the word count from a text.
