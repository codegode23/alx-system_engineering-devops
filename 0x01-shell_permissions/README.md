su command is used to run a command as a different user.
whoami is used to get the current user name.
groups is a command that prints all the groups the current user is part of.
chown is a command used to change the owner of a file. e.g "chown betty hello" will change the owner of the file "hello" to "betty".
touch is a command used to create a new file.
chmod u+x is a command that adds execute permission to the owner of a file. e.g "chmod u+x hello" adds execute permission to the hello file.
chmod ug+x,o+r is a command that adds execute permission to the owner and the group owner, and read permission to other users, to the file. .eg. "chmod ug+x,o+r hello" adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x is a command that adds execution permission to the owner, the group owner and the other users, to a file. e.g. "chmod ugo+x hello" that adds execution permission to the owner, the group owner and the other users, to the "hello" file.
chmod 007 is a command that gives no permission to both the owner and group of the file but grants users all permissions.
chmod 753 is a command that sets the mode of the file to all permissions for owner, only read and read and execute permission for the group and write and execute permission for the user.
chmod --reference=newmod old mode is a command that sets the mode of the file oldmode to that of newmod.
chmod -R ugo+X is a command  that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.Regular files are not changed.
mkdir -m 751 my_dir is a command that creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello is a command that changes the group owner to school for the file.
chown -hR vincent:staff . is a command that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
