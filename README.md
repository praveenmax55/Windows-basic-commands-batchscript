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

```
Name:Praveen D
Reg.No:212222240076
```

# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

![325137896-e20f8141-6596-43d5-b989-2d2dab0d0dda](https://github.com/praveenmax55/Windows-basic-commands-batchscript/assets/113497509/6345840f-cb59-4f3b-94a5-a8fe65442b47)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![325138032-d27849bc-c467-4873-8c79-f7428a160e8c](https://github.com/praveenmax55/Windows-basic-commands-batchscript/assets/113497509/365605d2-1770-466e-bb1d-faca5cdff74f)

![325138071-1fa80caf-e9f6-43b8-ae3b-32796202e14c](https://github.com/praveenmax55/Windows-basic-commands-batchscript/assets/113497509/814771fe-9b57-4ec3-b7fb-183934426e5c)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![325138202-40de307a-60ec-44ed-a9d2-94ed73c8d346](https://github.com/praveenmax55/Windows-basic-commands-batchscript/assets/113497509/b6162c2f-e393-43b1-a667-f2ce69a92fc0)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![325138344-47278c6b-2a0d-45f3-bdb9-2f0cc267fbc3](https://github.com/praveenmax55/Windows-basic-commands-batchscript/assets/113497509/369b7ae1-0483-4386-937e-d5073b91f591)

![325138398-364ae2ec-b6ff-4583-b92f-bbc9533b06d0](https://github.com/praveenmax55/Windows-basic-commands-batchscript/assets/113497509/bcdaf22e-2ef9-4729-a58a-7b359fc69474)



## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![325138492-99f98df3-adcf-47a5-befb-fdd0122af505](https://github.com/praveenmax55/Windows-basic-commands-batchscript/assets/113497509/6d4f632f-a010-40cc-89d3-7f5c13d28dfd)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT
![325138649-c9ec83f6-a056-4184-8124-df0c065cc7e9](https://github.com/praveenmax55/Windows-basic-commands-batchscript/assets/113497509/6ceecf3b-a7d0-4e6e-b34a-740e9bba8ac2)



# RESULT:
The commands/batch files are executed successfully.
