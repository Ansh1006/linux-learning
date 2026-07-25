Last time we did fundamentals of command line and moving around in linux. Now we learn how to handle folders and files.

## touch
It makes a file of whatever name you keep after `touch`.
*In linux what we use as extension like .mp4 or .exe doesn't matter cause the name might be video.mp4 while the file is actually a picture so we need to check what the file actually is.

#We can use `file` command to know the actual type of the file we are dealing with.

## cat 
This command has many good uses especially if you're just starting and don't know many other command in linux.
It lets you open files to see their content(if supported).
It can open up multiple files at once too.
It lets us make the file and then write something in it too unlike the `touch` command.

Example: cat > file1.txt

This will make the file if not there with the name of file1.txt and then we can write in it too.

## cp
This is the copy command. Basically lets us copy the files that we want.
We can use it's options to help in making mass-copying easy too.

#Wildcards:
*
[]
? 
#Usage:
1.) The star allows to copy all files of a certain type.
Example: `cp *.jpg` copies all .jpg files present in the directory.

2.) Any character written inside the large brackets will be found.
Example: `cp [rp]` copies all files with a "r" or a "p"  present in it.

3.) Matches any one character only.
Example: `cp ?r` finds all files with "r" present in it's name.

#Options:
-r
-i
-p
-v

#Usage:
1.) Copies entire directories with the sub-folders and files intact.

2.) Prompts for confirmation before overwriting a already existing file.

3.) Preserves the original stats of the file.

4.) Displays the name of each file as it is being copied. 

## mv
This is the move command.
Lets us move the files we want from one place to the other.
It can also change the name of the file if we want to while moving to a different directoy, or keep the directory same and change the name for using it like the rename feature.

Example: file1/Documents file2/Documents 

This renames the file from file1 to file2 while keeping the directory same.
# mv also has the same type of options like cp


## mkdir
This command lets us make directories.
#Use `mkdir -p` command to make sub directories inside the directories.(The -p stands for parent)

Example: /how/are/you
This will create a directory `how` in your current location. This `how` directory will contain directory `are` which in turn contains the `you` directory.

##rm
This command is used to remove the files and  directories.
Until some special command or option type of `rmdir` is used, it only removes empty directories.

#Options:
`-f `
`-rf`
`-i `
`-r `

#Usage:
1.) -f is for forceful file deletion.

2.) -rf is for forceful folder deletion

3.) -i is for interactive deletion. Basically asks to confirm what you are deleting

4.) -r is for directory removal.(deletes the directory even if something is present inside)

*rmdir: used for directory removal(the directory should be empty)
