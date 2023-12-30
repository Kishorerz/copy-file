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
# Developed by : KISHOR KUMAR B.
#RegisterNumber:212223240072
with open("basic.txt","r") as f:
    x=f.read()
with open("basic2.txt","w") as f1:
    f1.write(x)

```

### OUTPUT:
![Screenshot 2023-12-30 070048](https://github.com/Kishorerz/copy-file/assets/144451216/990bcbe0-5019-425e-8b2f-753cacf53557)

![Screenshot 2023-12-30 064807](https://github.com/Kishorerz/copy-file/assets/144451216/95f12af7-d951-4c86-a481-bc9142dfff76)
![Screenshot 2023-12-30 064728](https://github.com/Kishorerz/copy-file/assets/144451216/d1f36313-1800-42ae-b643-501339af833b)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
