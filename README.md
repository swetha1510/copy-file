# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Open a text file as firstfile using with open command

### Step 2: 
 Open another text file as secondfile using with open command
 
### Step 3: 
Using for loop , reading the content inside firstfile.

### Step 4:  
Copying first file in second file 

### Step 5: 
Run the Program. The First file will be copyed in second file

### Step 6: 
End the program.

## PROGRAM:

''' 
Program to copy the contents from one file to another file
Developed by: SWETHA P
RegisterNumber: 22008542

with open('new.txt','r') as firstfile:
    with open('file.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

### OUTPUT:
![AfterCopy](https://user-images.githubusercontent.com/119477975/214105415-bc357645-9f26-41c4-9ccd-7891b2dec183.png)
![BeforeCopy](https://user-images.githubusercontent.com/119477975/214105446-a045358c-a305-43e9-923a-0a7adcacd6bd.png)
![file](https://user-images.githubusercontent.com/119477975/214105506-bded885b-1b2b-4c99-b868-84de78af0f16.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
