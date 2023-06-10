# Read-from-CSV

## AIM:
To write a program for reading the csv file content.
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
<br>

### Step 2:
Print the number of contents to be displayed using df.head().
<br>

### Step 3:
The number of row returned is difined in pandas option settings.
<br>

### Step 4:
Check your systems maximum column with the pd.options.display.max_column statement.
<br>

### Step 5:
Increase the maximum  number of rows to display the entire DataFrame.
## PROGRAM:
```python
"""
Developed by: Sabari Akash A
Register no: 212222230124
"""
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no of rows",len(df.axes[1]))
```
## OUTPUT:
![output](/output.png)

## RESULT:
Thus the program executed successfully for read csv file.