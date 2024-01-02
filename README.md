# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Open the source file in read mode.

# Step 2:
Read the contents of the source file and store it in a variable

# Step 3:
Close the source file.

# Step 4:
Open the destination file in write mode. If the file doesn't exist, it will be created.

# Step 5:
Write the contents from the variable to the destination file.

# Step 6:
Read the contents of the destination file and print it to verify the copy operation.

# Step 7:
End the program

## PROGRAM:
```python
#Program to copy the text from one file to another
#Developed by :VIGNESH.V
#Register umber :23004027
f=open(r"/content/m.txt","r")
a=f.read()
print(a)
b=open(r"/content/mano.txt","w+")
b.write(a)
b.seek(0)
print(b.read())
```

### OUTPUT:
![Screenshot 2024-01-02 170731](https://github.com/23004027/copy-file/assets/138956447/062d8b23-9ecd-4552-971b-8c504bf0d1d7)
![Screenshot 2024-01-02 170126](https://github.com/23004027/copy-file/assets/138956447/54946533-a3dd-44c0-9622-de3c17978f7e)
![Screenshot 2024-01-02 171327](https://github.com/23004027/copy-file/assets/138956447/fe0df5a6-87ef-4472-ad2f-f56bfee57f05)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
