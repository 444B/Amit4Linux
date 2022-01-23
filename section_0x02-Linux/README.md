# Linux  
UNDER CONSTRUCTION  
This is the most important section and will be the focus of our sessions. We 
### Section Scope  
- An introduction to Linux that will begin with its history and conclude with being familiar with the concept of Linux OS
- An explanation of Open Source, the Core Ideology of Richard Stallman and the impact it has had on the world  
## Content  
### Readings / Clips  
- Watch [Vim in 100 Seconds](https://www.youtube.com/watch?v=-txKSRn0qeA)
- Watch [Weird History of Linux](https://www.youtube.com/watch?v=ShcR4Zfc6Dw)
- Watch [Linux Directories in 100 Seconds](https://www.youtube.com/watch?v=42iQKuQodW4)
- Watch [Bash in 100 seconds](https://www.youtube.com/watch?v=I4EWvMFj37g)
### Notes  
#### Commands
- tldr ~command~ == prints out the common use cases and purpose of a command
- cd == Change directory
    - cd == navigates to the user home
    - cd ~directory~ == navigates into a directory
    - cd .. == navigates up one directory level
- ls == lists contents of current directory ]
    - ls -lah == lists contents of current directory in long format, all files and in human readable format
- pwd == prints working directory
- nano ~file~ == opens a file and allows you to edit the text inside using the Nano text editor
- man ~command~ == shows the manual for the specific command
- apt ~command~
    - apt update == updates the latest software releases 
    - apt upgrade == upgrades the local software to the latest releases
    - apt install ~package name~ == installs the specified package to the machine
- rm == removes something
    - rm ~file~ == removes a file
    - rm -rf -directory- == removes a directory and its contents, no questions asked
- echo "STRING" == takes STRING as an input and prints it on the terminal as the output
- cat ~file~ == takes a file as an input and prints it on the terminal as the output
#### FUN commands
telnet towel.blinkenlights.nl
cmatrix
telnet
cowsay
fortune
#### Input/Output Redirection
- >> == APPEND the input to a file
- > == OVERWRITE the output to a file, erasing what was there previously (be careful)
- | == PIPE the Output of a command as the Input to a new command
### Discussion  
[ This is expected to take place live or online]
## Progression  
### Learning Outcomes  
- Understand the role Linux and Open source play in our world today  
- familiarity with Linux CLI  
- ability to navigate the Linux Filesystem Heirarchy  
- Familiarity with the concept of logging locally  
- how to read and write a bash script  
### Tasks    
- Get to level 4 of OverTheWire 
- Get up to 3_less of the [CLI Excercises repository](https://github.com/444B/CLI/tree/main/excercises) (more excercises may be added in time)
