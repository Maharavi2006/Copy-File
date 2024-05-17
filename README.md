# Copy-File
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
When done print "File copied sucessfully"
### Step 6: 
End of the program.
## PROGRAM:
```
#Developed by: Mahalakshmi R
#Reg No: 212223230117
with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![Screenshot 2024-05-12 135320](https://github.com/Mahalakshmi230/Copy-File/assets/149365324/74e4cf90-229e-4429-b44b-28115ad44a9a)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
