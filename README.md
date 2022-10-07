# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
assign value for num_word

### Step 2: 
open the file in read mode
 
### Step 3: 
iterate using for loop

### Step 4:  
increment the word with length of the word

### Step 5: 
print the number of words in text
## PROGRAM:
```python
##Developed by:yuvabharathi
##Register no:22002787

num_word=0
with open("My File.txt","r")as file1:
    for i in file1:
        word=i.split()
        num_word+=len(word)
print("number of words {}".format(num_word))
```

### OUTPUT:
![Screenshot from 2022-10-07 14-09-44](https://user-images.githubusercontent.com/113497404/194511995-c1ff9e89-da37-4abb-b945-8e2df8f3ab1a.png)

![Screenshot from 2022-10-07 14-11-59](https://user-images.githubusercontent.com/113497404/194512218-a640ee7a-5a60-43aa-aecd-d492c6f6d5de.png)


## RESULT:
Thus the program is written to find the word count from a text.
