script that switches the current user to the user betty. su betty
script that prints the effective username of the current user. whoami
script that prints all the groups the current user is part of. groups
script that changes the owner of the file hello to the user betty. chown betty hello
creat a file named hello. touch hello
script that adds execute permission to the owner of the file hello. chmod u+x hello
script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. chmod u+x, g+x, o+r hello
script that adds execution permission to the owner, the group owner and the other users, to the file hello. chmod a+x hello
. James Bond chmod 007 hello
cript that sets the mode of the file hello to this: chmod 753 hello
Write a script that sets the mode of the file hello the same as olleh’s mode. chmod --reference-olleh hello 
script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed. chmod -R +X
script that changes the group owner to school for the file hello chown school hello
