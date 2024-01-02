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
    with open("basic2.txt","w") as f1:
        x=f.read()
        f1.write(x)

```

### OUTPUT:

![Screenshot 2024-01-02 134807](https://github.com/Kishorerz/copy-file/assets/144451216/38b10f04-4ae7-45e8-8309-edadc30e620c)
### old basic2.txt
![Screenshot 2024-01-02 135752](https://github.com/Kishorerz/copy-file/assets/144451216/1f576d2e-3f17-4be1-8bcd-bdd774eb2bc5)


![Screenshot 2024-01-02 134819](https://github.com/Kishorerz/copy-file/assets/144451216/fefab326-24bc-4fb8-8d54-276ba24e0805)
### new basic.txt
![Screenshot 2024-01-02 134757](https://github.com/Kishorerz/copy-file/assets/144451216/947196d9-6284-4eba-9bbb-3535029c8378)






## RESULT:
Thus the program is written to copy the contents from one file to another file.
