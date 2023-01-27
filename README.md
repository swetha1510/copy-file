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

```
Program to copy the contents from one file to another file
Developed by: SWETHA P
RegisterNumber: 22008542

with open('new.txt','r') as firstfile:
    with open('file.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

### OUTPUT:
### Before copying:

![beforecopy1](https://user-images.githubusercontent.com/120623583/215112304-c1536f21-4d72-409c-a17e-e24acbcc4af2.png)

![beforecopy2](https://user-images.githubusercontent.com/120623583/215112386-6e8c4784-efbc-49d2-9db5-dbdffc3f9278.png)

### After copying:

![aftercopy](https://user-images.githubusercontent.com/120623583/215112505-0ee68a57-660c-4992-a538-b9af9b14bb38.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
