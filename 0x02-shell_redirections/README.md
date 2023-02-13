## Scripts and what they do

# echo "Hello, World" - This prints “Hello, World”, followed by a new line to the standard output.

# "\"(Ôo)'" - This  displays a confused smiley "(Ôo)'. Notice a backslash was used.

# cat - short for "concatenate" is a command that allows us to create single or multiple files, view content of a file, concatenate files and redirect output in terminal or files. cat /etc/passwd will Display the content of the /etc/passwd file.

# cat file1 file2 - This command helps you View Contents of Multiple Files in terminal.

# tail - This command Displays the last lines of a specified file's input. e.g. tail -n 10 /etc/passwd Display the last 10 lines of /etc/passwd.

# head - This command Displays the first lines of a specified file's input. e.g. head -n 10 /etc/paswwd displays the first 10 linnes of /etc.passwd

# head -n 3 iacta | tail -n 1 - a script that displays the third line of the file iacta.

# echo - a script used for displaying lines of text or string which are passed as arguments on the command line.

# ls -la > ls_cwd_content - This command writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it will be overwritten. If the file ls_cwd_content does not exist, it will be created.

# tail -n 1 iacta >> iacta - a script that duplicates the last line of the file iacta

# find . -type f -name "*.js" -delete - a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

# find . -type d -not -name '.' | wc -l  - a script that counts the number of directories and sub-directories in the current directory. Here The current and parent directories are not taken into account. Hidden directories are counted

# ls -t1 | head -n 10 - a script that displays the 10 newest files in the current directory. Here One file per line is displayed. The files are Sorted from the newest to the oldest.

# sort | uniq -u - a script that takes a list of words as input and prints only words that appear exactly once.
## 1. Input format: One line, one word
## 2. Output format: One line, one word
## 3. Words should be sorted

# grep -i "root" /etc/passwd  - A script that Display lines containing the pattern “root” from the file /etc/passwd.

# grep -c -i "bin" /etc/passwd  - This script Display the number of lines that contain the pattern “bin” in the file /etc/passwd.

# grep -i "root" -A 3 /etc/passwd - This script Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

# grep -i -v "bin" /etc/passwd  - this script Display all the lines in the file /etc/passwd that do not contain the pattern "bin".

# grep -i "^[a-z]" /etc/ssh/sshd_config - This script Display all lines of the file /etc/ssh/sshd_config starting with a letter.

# tr "A" "Z" | tr "c" "e" - this script will Replace all characters A and c from input to Z and e respectively.

# tr -d "cC"  - a script that removes all letters c and C from input.

# rev  -  a script that reverse its input.

# cut -d ':' -f 1,6 /etc/passwd | sort  -  a script that displays all users and their home directories, sorted by users. It is Based on the the /etc/passwd file.

# find . -empty | rev | cut -d '/' -f 1 | rev  -  a command that finds all empty files and directories in the current directory and all sub-directories.
## 1. Only the names of the files and directories are displayed
## 2. Hidden files are listed
## 3. One file name per line
## 4. The listing ends with a new line
