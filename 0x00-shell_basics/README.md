script that prints the absolute path name of the current working directory pwd
Display the contents list of your current directory ls
script that changes the working directory to the user’s home directory cd
Display current directory contents in a long format ls
Display current directory contents, including hidden files (starting with .). Use the long format ls -la
Display current directory contents ls -lna
script that creates a directory named my first directory in the /tmp/ directory mkdir /tmp/
Move the file betty from /tmp/ to /tmp/my_first_directory: mv /tmp/betty /tmp/my_first_directory
Delete the file betty. rm betty/tmp/my_first_directory
directory delete. rmdir tmp/my_first_directory
script that changes the working directory to the previous one. cd -
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format. ls -la . .. /boot
Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script. file /tmp/iamafile
 a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory. ln -s /bin/ls __ls__
script that copies all the HTML files from the current. cp -u *.html ..
Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u. mv [[:upper:]]* /tmp/u
