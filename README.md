# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

![image](https://github.com/Nishanth-018/Windows-basic-commands-batchscript/assets/149347651/0751e8e3-d976-4652-b6db-e3ce74337a8d)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/Nishanth-018/Windows-basic-commands-batchscript/assets/149347651/71395d2b-df65-45a6-a1cc-6979b2f7a6e4)
![image](https://github.com/Nishanth-018/Windows-basic-commands-batchscript/assets/149347651/7b97fdfa-bb78-4f6f-b9aa-7ce46e95e395)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/Nishanth-018/Windows-basic-commands-batchscript/assets/149347651/44bb691a-201a-4873-9fce-01e712768558)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![image](https://github.com/Nishanth-018/Windows-basic-commands-batchscript/assets/149347651/bcf10c4c-a318-4a9a-9c90-a29cbca66531)
![image](https://github.com/Nishanth-018/Windows-basic-commands-batchscript/assets/149347651/45fe24b3-bb6b-4f40-9a64-73f65531ab1a)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Nishanth-018/Windows-basic-commands-batchscript/assets/149347651/1ad0be2d-cd50-44f3-8d21-d061da6583b1)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT
![image](https://github.com/Nishanth-018/Windows-basic-commands-batchscript/assets/149347651/9903e0ff-74ff-4caa-a761-69bc157c3e7b)

## RESULT:

The commands/batch files are executed successfully.

