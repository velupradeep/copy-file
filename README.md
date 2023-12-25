# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:First we need to open the required the from which we need to copy the text

### Step 2: Using keyword "with" to open the required file
 
### Step 3: Using keyword "with" to open the required file

### Step 4: The empty file is open by using 'W' which is used to write only 

### Step 5:The for function is used to take each line from the main file 

### Step 6: Write() is used to write the lines of main file to the empty file or to the directed file

## PROGRAM:
```
with open("text.txt","r") as f1:
    data=f1.read()
with open("data.txt","w") as f2:
    f2.write(data)
```
## TEXT FILE:
```
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
```
## EMPTY FILE:
```
with open("data.txt","w") as fd:
 fd.write("")
```
## COPY FILE:
```
with open("data.txt","r") as f2:
  data1=f2.read()
  print(data)
```

### OUTPUT:
![1](https://github.com/velupradeep/copy-file/assets/150329341/60459f7e-9ee8-4445-8112-c6f56183960a)
![2](https://github.com/velupradeep/copy-file/assets/150329341/002a9115-b5b2-42bf-9bbe-8a1e3ada5dec)
![3](https://github.com/velupradeep/copy-file/assets/150329341/ba1ebb4b-b301-43d8-939c-941ed22af43e)
![4](https://github.com/velupradeep/copy-file/assets/150329341/8e4e138b-ea14-47e8-bfa3-8122cdfc5ee0)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
