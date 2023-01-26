# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
 Define the variable to count the number of words in the file and defined with 0.
### Step 2: 
 Open the text file using the with open keyword.
### Step 3: 
Using r command i.e:read mode.
### Step 4:  
Using for loop iterate the file to split the space in the words.
### Step 5: 
The splited and stored in the variable, use len() function of the splited word variable.
### Step 6: 
End the program.
## PROGRAM:
```
Developed by: LOKESH RAHUL V V
Register no: 22004702

num_words=0
with open('a.txt','r') as file1:         
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```
### OUTPUT:

![copy1](https://user-images.githubusercontent.com/118423842/214761948-cc5cda70-7421-4fee-981f-bdc3bb0f0452.jpg)
![copy2](https://user-images.githubusercontent.com/118423842/214761976-862d340f-5ec5-47d4-9627-226d6978d878.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
