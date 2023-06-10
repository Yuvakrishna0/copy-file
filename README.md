# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
get the input text file
### Step 2: 
Read the file
### Step 3: 
copy the file
### Step 4:  
display the file

## PROGRAM:
```
Developed by: Yuva krishna k
Reg no:21222110056

with open("text.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![244872077-5e74136c-124d-42ab-af7d-48a73a255e34](https://github.com/Yuvakrishna0/copy-file/assets/117915037/6fa4f797-e33b-4b10-8244-25af4955bf25)

![244872103-6cb8870e-260c-421e-90b4-8595e241da6e](https://github.com/Yuvakrishna0/copy-file/assets/117915037/22a95808-7047-4b20-ab81-7a23f0c1b1ce)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
