# Read-from-CSV

## AIM:
To read from CSV

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output:
```
## PROGRAM:
Developed by:Pavan Kishore.M
Ref.no:212221230076

import pandas as pd
f=pd.read_csv("/content/nba (2).csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/119389139/214855135-6f360a1b-30a1-4382-8b5e-afd4d18d19f7.png)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
