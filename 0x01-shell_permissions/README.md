The "su betty" command will change the current user to betty.
The "whoami" command will print the name of the current user.

"groups $USER" will print the groups the current user is part of.
"sudo chown betty hello" will make betty the owner of the "hello" file.

The "touch hello" command will create an empty hello file.
"chmod u+x hello" will give execute permission to the owner of the file.


"chmod 114 hello" will give execute permission to owner and group, and read permission to others.
"chmod 111 hello" will execute permission to owner, group, and others.

"chmod 007 hello" will give no permission to owner and group, but all permissions to others.
"chmod 753 hello" sets the mode to -rwxr-x-wx.

"chmod 664 hello" sets the mode to -rw-rw-r--
"chmod +111 ." adds execute permission to subdirectories of the current directory.

"mkdir -m 751 ./my_dir" creates a directory "my_dir" with the 751 permissions.
"chgrp school hello" will make "school" the new group owner of the hello file.
