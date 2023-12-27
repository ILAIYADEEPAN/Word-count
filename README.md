# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file with .txt file extension
### Step 2: 
  add some text in that file
### Step 3: 
create a python file

### Step 4:  
write a code to count the number of words in that file
### Step 5: 
run the program
### Step 6: 
display the output
## PROGRAM:
```
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Ttotal number of words:",count)
program()
```

### OUTPUT:
![word count](https://github.com/ILAIYADEEPAN/Word-count/assets/147473334/28a8784a-e81a-4046-aeec-690d4567dbb6)
![word count output 2](https://github.com/ILAIYADEEPAN/Word-count/assets/147473334/6779c201-1933-4585-a4d7-4a18b957da1a)
![word count output 3](https://github.com/ILAIYADEEPAN/Word-count/assets/147473334/d9097f4e-be92-47f0-97d0-a8edf1cf3bad)



## RESULT:
Thus the program is written to find the word count from a text.
