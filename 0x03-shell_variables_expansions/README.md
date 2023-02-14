0: create an alias: alias name=value
1: Create a script that prints hello user, where user is the current Linux user: echo "hello "$USER
2: Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program: PATH=$PATH:/action
3: script that counts the number of directories in the PATH: echo $PATH | tr ':' '\n' | wc -l
4: Create a script that lists environment variables: printenv
5: script that lists all local variables and environment variables, and functions: set
6: Create a script that creates a new local variable: name="value"
7: Create a script that creates a new global variable: export name="value"
8: Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
9: Write a script that prints the result of POWER divided by DIVIDE, followed by a new line: echo $((POWER / DIVIDE))
10: 10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath: echo $((BREATH ** LOVE))
11: Write a script that converts a number from base 2 to base 10: echo "$((2#$BINARY))"
12: Create a script that prints all possible combinations of two letters, except oo: echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"
