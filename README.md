# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
To write a python program for getting the word count from a text file

# Step 2:
Open the required file by using the function "with"

# Step 3:
Then use the laptop to assign the i value in the file

# Step 4:
Using split function to split the words

# Step 5:
Finding the given length of the words by using len() function

# Step 6:
Calling the function and Printing the number of words

## PROGRAM:
```
#Program to find the word count
#Developed by: Mani Sri Latha.M
#Register number: 23008627
file=input()
num=0
with open(file,'r') as f:
    for line in f:
        words=line.split()
        num+=len(words)
print('Number of words:',num)
```
### OUTPUT:
![Alt text](<No.of Words.png>)

## RESULT:
Thus the program is written to find the word count from a text.
