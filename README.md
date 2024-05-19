# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Prompt the user to enter the filename and store it in the variable filename.
### Step 2: 
 Initialize a variable num to 0.
### Step 3: 
Open the file using with open(filename, "r") as file: for proper file handling.
### Step 4:  
Iterate through each line in the file using for word in file:. Split each line into words: Word = word.split().
### Step 5: 
Update the word count: num = num + len(Word).
### Step 6: 
Print the total number of words in the file: print("Number of words in file:", num).
## PROGRAM:
filename=input("Enter filename:")
num=0
with open(filename,"r") as file:
    for word in file:
        Word=word.split()
        num=num+len(Word)
print("Number of words in file:",num)
### OUTPUT:
![Screenshot 2024-05-19 130813](https://github.com/Nakul1411/Command--line-arguments-to-count-word/assets/138849780/2aa588c2-f5c6-465f-8ab2-9c1e5ae5a733)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
