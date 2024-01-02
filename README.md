# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
import pandas pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.

## PROGRAM:
```
'''
#program to copy the file
#Developed by:NISHA.D
#Register number:212223230143
'''
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```

## OUTPUT:

![Alt text](<Screenshot 2024-01-02 180019.png>)


## RESULT:
Thus a python program is written to read the content of the CSV file.