# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.

### Step 2: 
Print the number of contents to be displayed using df.head().

### Step 3: 
The number of rows returned is defined in Pandas option settings.

### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5: 
Increase the maximum number of rows to display the entire DataFrame

### Step 6: 
End the program.

## PROGRAM:
```
#Program for copying the contents from one file to another file.
#Developed By: Dharshni V M 
#Register Number: 212223240029

with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![output](Output.png)
![text](<Text output.png>)
![copytext](<copy output.png>)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
