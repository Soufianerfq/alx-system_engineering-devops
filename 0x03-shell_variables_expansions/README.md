0: create an alias: alias name=value
1: Create a script that prints hello user, where user is the current Linux user: echo "hello "$USER
2: Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program: PATH=$PATH:/action
3: script that counts the number of directories in the PATH: echo $PATH | tr ':' '\n' | wc -l
4: Create a script that lists environment variables: printenv
5: script that lists all local variables and environment variables, and functions: set
6: Create a script that creates a new local variable: name="value"
