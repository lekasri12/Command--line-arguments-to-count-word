# EX-10 Command--line-arguments-to-count-word
# DATE
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function which will count the word in the given file.
### Step 2:
Create a file pointer and open the file.
### Step 3:
Initialize word count as zero.
### Step 4:
For each line in file, split it into words and find number of the words in every line.
### Step 5:
Sum the number of words in each line.
### Step 6:
Display the total words in the file.
### Step 7:
Close the file pointer and end the program. 

## PROGRAM:
```
# Program to find Command--line-arguments-to-count-word
# Developed by: G LEKASRI
# Register no: 212223100025

import sys
fp=open(sys.argv[0])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()

```
### OUTPUT:

![Screenshot 2024-10-16 144038](https://github.com/user-attachments/assets/acc6ee76-e02f-4ea5-b289-af2195eada20)


![Screenshot 2024-10-16 144056](https://github.com/user-attachments/assets/abcd476a-8438-4524-8e52-0b8fd80232a9)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
