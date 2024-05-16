# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the Function: Start by defining the function copy that takes two parameters: fname and newfile.
### Step 2: 
Open the Source File: Use the open() function to open the source file (fname) in read mode. Use a context manager (with statement) to ensure that the file is properly closed after reading.
### Step 3: 
Open the Destination File: Similarly, open the destination file (newfile) in write mode. Again, use a context manager to ensure proper file handling.
### Step 4:  
Read Data from Source File: Use the read() method to read the contents of the source file (fp) and store it in a variable (data).
### Step 5: 
Write Data to Destination File: Use the write() method to write the contents of the data variable to the destination file (fp1). This effectively copies the contents of the source file to the destination file.
### Step 6: 
Close Files: Close both files using the context managers to ensure that all resources are properly released.

## PROGRAM:
```
def copy(fname,newfile):
    with open(fname) as fp:
        with open (newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("file1.txt","file2.txt")
```
### OUTPUT:
![image](https://github.com/Ravi-1105/Copy-File/assets/139841688/ac9095a0-b047-4ffc-86a4-e68d3b8fd902)
![image](https://github.com/Ravi-1105/Copy-File/assets/139841688/e7989ec4-59a5-4588-9934-728984b2f5db)
![image](https://github.com/Ravi-1105/Copy-File/assets/139841688/b5fea89b-f66b-4b80-946b-c6e91c3448ab)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
