# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Decleare number of words is 0

### Step 2:open it with txt file
 
### Step 3: Give range for i

### Step 4:  Then nxt split the words

### Step 5: count the number of words

### Step 6: Giving print statement for getting output.

## PROGRAM:
```
'''Program to count the words in a file
Developed by: Naveen Raja N.R
Register Number: 212222230093
'''
fname=input("enter the file name")
num_words=0
with open(fname, 'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)
```


### OUTPUT:


![naveen py xp 5a ](https://github.com/naveenraja2004/Word-count/assets/118707204/98f5c893-8e84-477b-a1f8-c59162a756e9)

## RESULT:
Thus the program is written to find the word count from a text.
