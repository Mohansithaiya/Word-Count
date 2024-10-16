# DATE:
# EX.NO.09 Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2: 
Read the text using read() function. 
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```PYTHON
##DEVELOPED BY: MOHAN S
##REFERENCE NUMBER: 212223240094
num_words =0
file1 = open("text.txt", "r")
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
## TEXT FILE:
```
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
```
### OUTPUT:

![Screenshot 2024-10-16 123754](https://github.com/user-attachments/assets/3693bca8-beb7-437b-8698-962818eb6820)

## RESULT:
Thus the program is written to find the word count from a text.
