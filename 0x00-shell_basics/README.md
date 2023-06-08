# Short description of the functions of the following script:

- **"The ./0-current_working_directory script"** prints the absolute path name of the current working directory using the "pwd" shell command.
- **The 1-listit script** lists the contents of the current working directory of the user. It does this with the "ls" script command.
- **The 2-bring_me_home script** changes the working directory to the user’s home directory by using the "cd ~" shell command.
- **The 3-listfiles script** displays the contents of the current directory of the user in a long format. It uses the "ls -l" command to achieve that. 
- **The 4-listmorefiles script** shows the contents of the current working directory contents of the user, including their hidden files (starting with .) in a long format by using the "ls -1 -al" script command.
- **The 5-listfilesdigitonly script** prints the display current directory contents. It does so by printing its long format alongside their user and group IDs, numerically,
and hidden files (starting with .).
- **The 6-firstdirectory script** creates a script that creates a directory named my_first_directory in the /tmp/ directory.
- **The 7-movethatfile script** moves the file betty from /tmp/ to /tmp/my_first_directory. 
- **The 8-firstdelete** deletes the file "betty" in the /tmp/my_first_directory directory.
- **The 9-firstdirdeletion** deletes the directory my_first_directory that is in the /tmp directory. 
- **The 10-back script** writes a script that changes the working directory to the previous one.
- **The 11-lists script** writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
- **The 12-file_type script** writes a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
- **The 13-symbolic_link script** creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
- **The 14-copy_html script** creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
- **The 100-lets_move script** creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
- **The 101-clean_emacs script** creates a script that deletes all files in the current working directory that end with the character ~.
- **The 102-tree script** creates a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
- **The 103-commas script** writes a command that lists all the files and directories of the current directory, separated by commas (,).
- **The school.mgc script** creates a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
