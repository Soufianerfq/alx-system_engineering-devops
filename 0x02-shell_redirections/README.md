0: print hello world
1: print a smile: echo '"(Ôo)'\'
2: display content of a of a file: cat  etc/passwd
3: display content of 2 fles: cat file1 file2
4: display last 10 lines of a file: tail file
5: display first 10 lines of a file: head file name
6: display the 3rd line of a file: head -3 file name | tail -1
7: creat a file with a weird long name.
8: Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it: ls -la > file name
9: script that duplicates the last line of the file iacta: tail -1 < iacta >> iacta
10: script that deletes all the regular files
11: Write a script that counts the number of directories and sub-directories in the current director: find . -type d -not -name '.' | wc -1
12: script that displays the 10 newest files in the current directory:  ls -t1 | head
13: script that takes a list of words as input and prints only words that appear exactly once. sort | uniq -u
14:Display lines containing the pattern “root” from the file /etc/passwd: grep -i "root" /etc/passwd
15: Display the number of lines that contain the pattern “bin” in the file /etc/passwd: grep -i "bin" /etc/passwd | wc -l
16: Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
17: Display all the lines in the file /etc/passwd that do not contain the pattern “bin" :grep -i -v "bin" /etc/passwd
18:Display all lines of the file /etc/ssh/sshd_config starting with a letter. grep -i "^[a-z]" /etc/ssh/sshd_config
19: Replace all characters A and c from input to Z and e respectively: tr "A" "Z" | tr "c" "e"
20: Create a script that removes all letters c and C from input: tr -d "cC"
21: Write a script that reverse its input.: rev
22: Write a script that displays all users and their home directories, sorted by user: cut -d ':' -f 1,6 /etc/passwd | sort
