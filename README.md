# command-line-arguments-to-count-word

## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:

Import sys module

### Step 2:

Open the file with sys.argv[1]

### Step 3:

Use the for loop to select the content in file

### Step 4:

Use split function to to separate the file content into words or strings

### Step 5:

Count the length of the words using len

### Step 6:

Print the number of words




## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: Renuga.S
RegisterNumber: 212222230118

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```


### OUTPUT:

![Screenshot from 2023-06-04 18-13-36](https://github.com/RENUGASARAVANAN/command-line-arguments-to-count-word/assets/119292258/eff7e9c1-a18f-45a9-b866-c70987f9d3da)

![Screenshot from 2023-06-04 18-13-54](https://github.com/RENUGASARAVANAN/command-line-arguments-to-count-word/assets/119292258/9c4aa69d-8345-4266-ae99-e8fb1de9d751)

![Screenshot from 2023-06-04 18-14-26](https://github.com/RENUGASARAVANAN/command-line-arguments-to-count-word/assets/119292258/f2d9ba28-dfc1-4598-b54e-74fe39859940)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
