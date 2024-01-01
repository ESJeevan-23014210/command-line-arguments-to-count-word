# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import pandas as pd
### Step 2:
Read the CSV file using_csv method
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the required contents from the file.
### Step 5:
Print the output

## PROGRAM:
```
# Program to read contents from a csv file
# DEVELOPED BY: Jeevan E S
# REGISTER NUMBER: 212223230091
 
import pandas as pd 
df=pd.read_csv('cars.csv') 
print(df.head(10)) 
print(df.tail(5)) 
print("Number of rows:",len(df.axes[0])) 
print("Number of columns:",len(df.axes[1]))
```
### OUTPUT:
![output](/output.jpeg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
