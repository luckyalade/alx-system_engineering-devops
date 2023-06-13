## Short description of the functions of the following script:

- **The 0-hello_world script** writes a script that prints *“Hello, World”*, followed by a new line to the standard output.

- **The 1-confused_smiley script** writes a script that displays a confused smiley *"(Ôo)"*.

- **The 2-hellofile script** displays the content of the */etc/passwd* file.

- **The 3-twofiles script** displays the content of */etc/passwd* and */etc/hosts* files.

- **The 4-lastlines script** displays the last 10 lines of */etc/passwd* file.

- **The 5-firstlines script** displays the first 10 lines of */etc/passwd* file.

- **The 6-third_line script** writes a script that displays the third line of the file iacta. The file *"iacta"* is reposed in the working directory exepting the use of the *"sed"* command.

- **The 7-file script** writes a shell script that creates a file named exactly *"\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)"* containing the text Best School ending by a new line.

- **The 8-cwd_state script** writes a script that writes into the file *"ls_cwd_content"* the result of the command *"ls -la"*.

- **The 9-duplicate_last_line script** writes a script that duplicates the last line of the file *"iacta"* The file *"iacta"* will be in the working directory.

- **The 10-no_more_js script** writes a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders. 

- **The 11-directories script** writes a script that counts the number of directories and sub-directories in the current directory.The current and parent directories were not taken into account, while hidden directories were counted.

- **The 12-newest_files script** creates a script that displays the 10 newest files in the current directory, with one file per line and sorted from newest to oldest. 

- **The 13-unique script** creates a script that takes a list of words as input and prints only words that appear exactly once.
    - Input format: One line, one word
    - Output format: One line, one word
    - Words should be sorted

- **The 14-findthatword script** displays lines containing the pattern *“root”* from the file */etc/passwd*.

- **The 15-countthatword script** displays the number of lines that contain the pattern *“bin”* in the file */etc/passwd*.

- **The 16-whatsnext script** displays lines containing the pattern “root” and 3 lines after them in the file */etc/passwd*.

- **The 17-hidethisword script** displays all the lines in the file */etc/passwd* that do not contain the pattern *“bin”*.

- **The 18-letteronly script** displays all lines of the file */etc/ssh/sshd_config* starting with a letter, with capital letters included.

- **The 19-AZ script** replaces all characters *A* and *c* from input to *Z* and *e* respectively.

- **The 20-hiago script** creates a script that removes all letters *c* and *C* from input.

- **The 21-reverse script** writes a script that reverse its input.

- **The 22-users_and_homes script** writes a script that displays all users and their home directories, sorted by users, based on the the */etc/passwd* file.

- **The 100-empty_casks script** write a command that finds all empty files and directories in the current directory and all sub-directories.
      - Only the names of the files and directories are displayed (not the entire path).
      - All Hidden files are listed.
      - They are a file name per line.
      - The listing ends with a new line.
      - Without basenames such as grep, egrep, fgrep or rgrep.

- **The 101-gifs script** writes a script that lists all the files with a *.gif* extension in the current directory and all its sub-directories.
      - Hidden files are listed.
      - Regular files (not directories) are listed.
      - Names of the files are displayed without their extensions.
      - Files are sorted by byte values, but case-insensitive. 
      - One file per line.
      - Listing ends with a new line
      - Without basenames such as grep, egrep, fgrep or rgrep.

- **The 102-acrostic script** creates a script that decodes acrostics that use the first letter of each line. 

- **The 103-the_biggest_fan script** writes a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. And they are:
      - Ordered by number of requests, most active host or IP at the top.
      - Without basenames such as grep, egrep, fgrep or rgrep.
