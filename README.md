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
%userprofile%\Desktop\MyLab 
![326150191-c206b1a2-a6cd-4a05-8be1-0e757209c1bd](https://github.com/Kavi45-msk/Windows-basic-commands-batchscript/assets/147457752/842a1f6c-05fd-4c2c-9b93-560f68a1a806)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![326150288-4b447d26-41f7-404f-9b36-abeade389383](https://github.com/Kavi45-msk/Windows-basic-commands-batchscript/assets/147457752/4a2b1c71-8e67-4f8b-851f-f3dca9c22ded)
![326150304-5fdde096-136f-429f-b875-df720b5ace5f](https://github.com/Kavi45-msk/Windows-basic-commands-batchscript/assets/147457752/0df5d972-4737-44a8-94fb-a8bce6fd0c4b)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab
![326150376-d7c09055-e3c0-40a6-acc8-9c7a0d074a87](https://github.com/Kavi45-msk/Windows-basic-commands-batchscript/assets/147457752/a01b8983-3795-4c8d-9aa1-9fb4bd5e4059)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir 
%userprofile%\Desktop\Backup
![326150461-7ec9d35f-de3b-471f-a9ca-6f2a6d423eb2](https://github.com/Kavi45-msk/Windows-basic-commands-batchscript/assets/147457752/ab01afd0-e0ea-442b-8fdb-5a7a5ac4ecc9)
![326150446-b745898c-a420-4802-8b01-515134b5f90a](https://github.com/Kavi45-msk/Windows-basic-commands-batchscript/assets/147457752/60b897cd-2c57-422b-a292-1d1a143da56e)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![326150513-2a79b20b-4617-4582-afe4-b7b93fb63e29](https://github.com/Kavi45-msk/Windows-basic-commands-batchscript/assets/147457752/d2c7090b-25cb-4feb-93f0-b387bcea9f90)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!






## OUTPUT
![326150530-404d9504-2a72-4f94-aaed-bc617279bb62](https://github.com/Kavi45-msk/Windows-basic-commands-batchscript/assets/147457752/1a3f4695-59ad-42d3-887e-6b4de29e99a8)





# RESULT:
The commands/batch files are executed successfully.

