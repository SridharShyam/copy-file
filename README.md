# copy-file
### NAME: SHYAM.S
### REG.NO: 23012478
### DEPT: AIML
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file with some content in it.
### Step 2: 
Open the created text file.
### Step 3: 
Create another empty text file.
### Step 4:  
Copy the content of text file to empty file using write function.

## PROGRAM:
#Program for copying the contents from one file to another file
#Developed by: SHYAM S
#Register Number: 23012478

with open("shyam.txt",'r') as file1:
    msg=file1.read()
with open("shyamnew.txt",'w') as file2:
    file2.write(msg)
    

## OUTPUT:
![Screenshot 2024-01-02 184830](https://github.com/SridharShyam/copy-file/assets/144871368/1f70e550-3d82-4187-922c-f3c61f030c8a)

![Screenshot 2024-01-02 184842](https://github.com/SridharShyam/copy-file/assets/144871368/a1085f69-2946-4583-b7fa-5407ebf6dbd3)

![Screenshot 2024-01-02 184925](https://github.com/SridharShyam/copy-file/assets/144871368/8e2ad041-c1a3-409a-a12c-6b340c966bc1)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
