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
