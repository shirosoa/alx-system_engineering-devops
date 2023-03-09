su betty: Will switch the current user to the user betty.
whoami: Prints effective username of the current user.
groups: Prints all the groups the current user is part of.
chown betty hello: Changes the owner of the file hello to the user betty.
touch hello: Creates an empty file called hello.
chmod u+x hello: Adds execute permission to the owner of the file hello.
chmod ug+xo+r hello: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod 111 hello: Adds execution permission to the owner, the group owner and the other users, to the file hello.
chmod 753 hello: Sets the mode of the file hello to: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
chmod --reference=olleh hello: Sets the mode of the file hello the same as olleh’s mode.
chmod -R 111 * /: Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
mkdir -m 751 my_dir: Creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello: Changes the group owner to school for the file hello.
chmod vincent:staff * : Changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown -h vincent:hello _hello: Changes the owner and the group owner of _hello to vincent and staff respectively.
