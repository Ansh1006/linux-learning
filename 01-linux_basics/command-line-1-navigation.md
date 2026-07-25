# The Command line:
It's the most thing for a professional relying on linux. It lets us communicate to the computer system in a more efficient way.

#### Opening the command line from keyboard: ctrl+alt+t

#Linux Command line basics:

## pwd
Prints the absolute path of the directory we are currently present in.

Example: if we are present in Documents, it will print => /home/user/Documents

## ls
lists files and directories of the directory you are currently present in until specified.

Example: if we are present in user, it prints all the things presnt in user directory.

### Some useful options:
`ls -l`
`ls -a`
`ls -r`

"-l" displays the long form of the files and directories.
"-a" displays the hidden files and directories too.
"-r" displays everything in reverse alphabetical order i.e z-a.

#### We can combine these options too, like, ls -la displays all files and directories be it hidden or no in long format.

## cd
Allows us to change the directory using either absolute or relative path.

Example: using, `cd /home/user/Documents` while being in root directory will take you to Documents.

#### Some essential navigation shortcuts:
`cd. `
`cd..`
`cd~ `
`cd- `

"." represents the current directory you are in.
".." takes you to the parent directory of the directory you are in.
"~" takes you to your home directory.
"-" takes you to the last directory you were in.

# Absolute vs Relative paths:
Absolute paths are routes taken to reach a certain location or directory from anywhere, basically this path holds true everywhere.
Relative path relies on where you currently are. If you are in Documents then reaching home directory is like go back to parent directory 2 times and you will reach home. But if you remember the Absolute path you can reach wherever you want to.
