# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
 assign a variable count=0
### Step 3: 
open a file in read mode
### Step 4:  
iterate a variable through the file
### Step 5: 
assign a variable words=lines.split()
### Step 6: 
now iterate through the variable and increase the counyt and print the count value
## PROGRAM:
import sys fp = open(sys.argv[1]) as fp A = fp.read() count=0 V=A.split() for i in V: count+=1 print("count",V) print("count",count)
### OUTPUT:
![output](https://github.com/VINUTHNA-2004/command-line-arguments-to-count-word/commit/a6e63769dbba3d63f8d75f1460dfc07e962a8f3a)?raw=true


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
