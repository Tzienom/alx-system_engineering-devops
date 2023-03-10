The "pwd" command is to print the current working directory.
The "ls" command is to list the contents of the current working directory.

The "cd ~ (tilde)" command is used to take the user to home directory.
The "ls -l" command is used to list files in long format.


The "ls -la" command is used to list files in long format - hidden files inclusive.
The "ls -lna" command lists files and contents with user IDs in long format - hidden files inclusive:
ls: list contents of directory.
-l: enable long format.
-n: use users ID instead of their names.
-a: display hidden files.


The "mkdir /tmp/my_first_directory" command creates the specified directory in tmp.
The "mv /tmp/betty /tmp/my_first_directory" command moves the file betty to the specified directory.

The "rm /tmp/my_first_directory/betty" command will delete betty file from the specified directory.
The "rmdir /tmp/my_first_directory" command will delete the directory my_first_directory.

The "cd -" command will go back to the previous working directory.
The "ls -la /boot" prints all files in long format including hidden files, current working directory and parent directory.

The "file" command displays info about the specified file.
The "ln -s" creates a symbolic link and points to the intended file.

The "cp -u" copies files that are newer in the current directory.
"mv [:upper:] /tmp/u" will move any file with an uppercase letter.

"rm *~ ." will delete all files ending with ~ (tilde).
"mkdir -p ./welcome/'welcome to'/'welcome to school'" creates the subdirectories within the current working directory.

"echo $(ls -p | sed ':a;N;$!ba;s/\n/, /g')" will list all contents in the current directory as comma-separated items, and the directories will be printed with a slash.
