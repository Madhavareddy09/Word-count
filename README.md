# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
User Input:

Prompt the user to enter the name of the file they want to analyze.
### Step 2:
Initialize Word Count:

Set up a variable (word_count) to keep track of the total number of words in the file, starting at zero.
### Step 3:
Open and Read File:

Use the with open statement to open the specified file in read-only mode. This ensures proper handling of the file.
### Step 4:
Iterate Through Each Line:

Use a for loop to go through each line in the opened file.
### Step 5:
Count Words in Each Line:

Split each line into words using the split method and add the count of words to the word_count variable.
### Step 6:
Display Result:

After processing all lines, print the total number of words in the file.

## PROGRAM:
```
# Program to count the no.of word count
# Developed by : K Madhava Reddy
# Register Number : 212223240064
fname=input("Enter the file name ")
word_count=0
with open(fname,'r') as fp:
    for line in fp:
        words = line.split()
        word_count+=len(words)
    print("Number of words:",word_count)
```
### OUTPUT:
![image](https://github.com/Madhavareddy09/Word-count/assets/145742470/a4e48e0a-43f6-4a25-b2b8-1690acd0601f)

<br>

![image](https://github.com/Madhavareddy09/Word-count/assets/145742470/aff31307-0425-40e8-b36b-c8321dc05ca8)



## RESULT:
Thus the program is written to find the word count from a text.
