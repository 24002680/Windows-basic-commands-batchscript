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

Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it. mkdir %userprofile%\Desktop\MyLab

List the contents of the "MyLab" directory. cd %userprofile%\Desktop\MyLab

Copy "MyFile.txt" to a new folder named "Backup" on the desktop. dir %userprofile%\Desktop\MyLab

Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup

mv Myfile.txt %userprofile%\Documents


![Screenshot (305)](https://github.com/user-attachments/assets/a192760b-173d-47b7-bf28-6de1742768ac)



## Exercise 2: Advanced Batch Scripting

Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!



## OUTPUT

![328574602-1e8bd16c-f8d8-460c-8330-25beff843206](https://github.com/user-attachments/assets/27439c4b-3be2-4db4-bbcd-7c46ca88c3fc)





# RESULT:
The commands/batch files are executed successfully.

