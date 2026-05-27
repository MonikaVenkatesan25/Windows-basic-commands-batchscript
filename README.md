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
<img width="885" height="67" alt="image" src="https://github.com/user-attachments/assets/c06cc4d4-0ea4-45e0-a4f1-2100b5f00117" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="884" height="95" alt="image" src="https://github.com/user-attachments/assets/9b0648d2-189c-4d3d-948a-09627303bf62" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="911" height="417" alt="image" src="https://github.com/user-attachments/assets/5c870f61-e0bf-4d7f-8934-cfaff20ff4ad" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="329" height="128" alt="image" src="https://github.com/user-attachments/assets/373bb47b-dba5-4532-9193-d1f7e3db61ae" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="933" height="185" alt="image" src="https://github.com/user-attachments/assets/8be6a7e9-28d8-45a9-b514-08a74f38ac66" />
<img width="439" height="160" alt="image" src="https://github.com/user-attachments/assets/17bcf1da-8436-4c63-87df-e6663e47d6ac" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="896" height="270" alt="image" src="https://github.com/user-attachments/assets/94046102-d5b9-45b2-85a3-ec72e81901f7" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="905" height="401" alt="image" src="https://github.com/user-attachments/assets/ec690d3b-0f32-45a8-ae29-ae5df175cf42" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="941" height="434" alt="image" src="https://github.com/user-attachments/assets/22a234b7-a4c4-47e5-bc0e-1b9939f824d0" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="936" height="281" alt="image" src="https://github.com/user-attachments/assets/3453f501-898b-4c64-becb-7fb6c8562a6d" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="897" height="87" alt="image" src="https://github.com/user-attachments/assets/d86a9767-e6ad-4883-af36-4582baec08d0" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="822" height="234" alt="image" src="https://github.com/user-attachments/assets/b9936e17-98c7-41a4-a60b-09ec1769bf50" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="782" height="176" alt="image" src="https://github.com/user-attachments/assets/3dd3c260-de28-4b45-a36d-0df36d7ffe21" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="945" height="360" alt="image" src="https://github.com/user-attachments/assets/d68cbd0b-7cb8-4698-8f7b-604e4fca2075" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="915" height="396" alt="image" src="https://github.com/user-attachments/assets/c5a94d0b-4f82-4a36-9700-10096646eaa9" />


# RESULT:
The commands/batch files are executed successfully.

