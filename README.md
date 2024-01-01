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
# Developed by : dharshan pt
#RegisterNumber:23005803
with open("file1.txt","r") as f:
    x=f.read()
with open("file2.txt","w") as f1:
    f1.write(x)
```
### OUTPUT:
![Screenshot 2024-01-01 223346](https://github.com/AkilaMohan/copy-file/assets/138849376/665e0d9d-6211-46bd-8151-dfb736bbc7ed)
![Screenshot 2024-01-01 223421](https://github.com/AkilaMohan/copy-file/assets/138849376/354b5d72-a116-4616-8d3f-5289a10a5b49)
![Screenshot 2024-01-01 223432](https://github.com/AkilaMohan/copy-file/assets/138849376/03e60dfc-90ae-413e-a045-c15a0ee03116)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
