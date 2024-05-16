# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

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
