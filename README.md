# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT

Remove the directory "my-folder"


![os ex08-1](https://github.com/user-attachments/assets/a0ad6945-3ed0-4488-a7fb-f3d59ed2ec77)

## COMMAND AND OUTPUT


Create the file Rose.txt

![os ex08-2](https://github.com/user-attachments/assets/b48da456-e708-4282-b13a-9f3627cf4be5)


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection


![os ex08-3](https://github.com/user-attachments/assets/c5ba58f2-63d0-4529-9b9f-2daab7632007)


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

![os ex08-4](https://github.com/user-attachments/assets/e624186d-f166-4c75-a794-b6bd3c12539f)


## COMMAND AND OUTPUT

Remove the file hello1.txt

![os ex08-5](https://github.com/user-attachments/assets/b75c14bd-c23a-4310-9f32-cc8fc6a0b9b1)


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

List out all the associated file extensions 



![os ex08-6](https://github.com/user-attachments/assets/e1734fed-4766-4a18-ae66-3c7c88c9f19e)


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt


![os ex08-7](https://github.com/user-attachments/assets/2d2115e3-f1b4-4ce2-9a34-91991744276c)


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT


![os ex08-8](https://github.com/user-attachments/assets/832f5d9f-ce21-41c6-ad6a-5016ebfa65d9)


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.


## OUTPUT

![os ex08-9](https://github.com/user-attachments/assets/33598612-62da-4aad-a8d0-ab997ce24c04)


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

![os ex08-10](https://github.com/user-attachments/assets/69e2223f-8f6f-4c1a-b989-078557f52363)



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


![os ex08-11](https://github.com/user-attachments/assets/0ee7c673-8e25-4969-b6ed-4e9622249304)


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT


![os ex08-12](https://github.com/user-attachments/assets/f2ea3ce9-af85-41cc-8c88-3f86e92a2c73)


# RESULT:
The commands/batch files are executed successfully.

