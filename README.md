# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.
### Step 2: 
 Give a new file name to create a copy of a file content.
### Step 3: 
Read the file and close the file.
### Step 4:  
Now write the content in the new file.
### Step 5: 
When done print"File copied successfully".
### Step 6: 
End of the program
## PROGRAM:
```
# To write a program for coping the contents from one to another file.
# Developed by : VEERARAGAVAN V
#RegisterNumber:212223230237
with open("file1.txt","r") as f:
    x=f.read()
with open("file2.txt","w") as f1:
    f1.write(x)
```
### OUTPUT:
![Screenshot 2023-12-31 144003](https://github.com/veerargavanv27/copy-file/assets/138955645/0e25dfaf-6f4b-471a-a0d9-c729487eb516)
![Screenshot 2023-12-31 143709](https://github.com/veerargavanv27/copy-file/assets/138955645/eeba6011-f9bd-462a-9b2e-2ed047616e0d)
![Screenshot 2023-12-31 143718](https://github.com/veerargavanv27/copy-file/assets/138955645/8137d5ac-1a72-4a26-83e3-ea9bc4dc60cb)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
