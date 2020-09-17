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

Press the up arrow to have the last command appear again. 

Make new directory
```mkdir <directory>```

Remove existing directory 
```rmdir <directroy>```

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

To select all files and move them to the directory above use
```mv * ../```
(same rule applies as with cd ....)

# Vim Instructions
Vim is what we use to access code and other types of files. It's a bit tricky but not too bad once you get used to it.

to edit the file ```i```

to save ```:w```

to save and quit the file ```esc``` press ```:wq```

to forcefully exit press
```:q!```



# Python Instructions

Write `python` to access interpreter

Write `python File_name.py` to execute pythom file 

