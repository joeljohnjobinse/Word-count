# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the required file by using the function 'with'
### Step 2: 
Use a for loop to iterate the content in the file
### Step 3: 
Use the split function to split the words
### Step 4:  
Find the given length of the words using len() function
### Step 5: 
Call the function
### Step 6: 
Print the number of words
## PROGRAM:
#Program to find the number of words
#Developed by: Joel John Jobinse
#Register Number: 212223240062
with open("file1.txt",'r') as fp:
    noofwords=0
    for line in fp:
        words=line.split()
        noofwords+=len(words)
    print("No of words in file:", noofwords)
### OUTPUT:
![py5a](https://github.com/joeljohnjobinse/Word-count/assets/138955488/cc324d39-d9a9-45d5-8f60-12e86b8d4c96)

## RESULT:
Thus the program is written to find the word count from a text.
