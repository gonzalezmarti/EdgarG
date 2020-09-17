# Edgar Gonzalez Martinez
This README.md file is intended to be a resource for myself and others. If anything can be improved or added please let me know.

# GitHub Commands
The following set of commands are intended for uploading all your files in a given repostory to GitHub. These command guarantee all your files will be saved if:
-A repository allready exists by the same name as the directory
-You enter all necessary username and password info

```
git pull
git add --all
git status
git commit -m "Commit Message"
git stash
git push
```




# Command Line Instruction
Below are some basic commands intended to get you started with the command line. The command line is a simple way to access, edit and run files simutaneously. 

Go to the home directory.
```cd```

Change directory.
```cd <directory>```

Up one directory. 
```cd ..```

If more periods are added then you will go up that many more directories. For example ```cd ....``` will take you up 3 directories. 

Display files/directories within directory
```ls```

Make new directory
```mkdir <directory>```

Remove folder
```rm <foldername>```

Remove file
```rm <filename.filetype>```

Make new python file as well as to edit it if the file already exists.
```vim file_name.py```

To move a file into another place use 
```mv <filename> <directory/folder>```

The above command can also be used to rename a file. If the second <directory/folder> does not exist, it will renamed to that new one. For example, 
```mv <old_name> <new_name>```

Furthemore if more than one file need to be transferred, you can add more files to the command and they will all be put into the final file. 
```mv <first_file> <second_file> <directory> #both files will be put into directory```

To select all files and move them to the directory above use (same rule applies as with cd ....)
```mv * ../```






#vim instructions

to edit the file press `i`

to save press `:w`

to save and quit the file press `esc` press `:wq

to forcefully exit press
```:q!```



#python instructions

press `python` to access interpreter

press `python File_name.py` to execute pythom file 

