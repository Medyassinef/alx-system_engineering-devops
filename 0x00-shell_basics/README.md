0. Where am I? : a script that prints the absolute path name of the current working directory.
1. What’s in there? : display the contents list of your current directory.
2. There is no place like home : a script that changes the working directory to the user’s home directory.
3. The long format : display current directory contents in a long format.
4. Hidden files : display current directory contents, including hidden files (starting with .). Use the long format.
5. I love numbers : display current directory contents.
6. Welcome : a script that creates a directory named my_first_directory in the /tmp/ directory.
7. Betty in my first directory : it moves the file betty from /tmp/ to /tmp/my_first_directory.
8. Bye bye Betty : it deletes the file betty.
9. Bye bye My first directory : it deletes the directory my_first_directory that is in the /tmp directory.
10. Back to the future : a script that changes the working directory to the previous one.
11. Lists : a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12. File type : a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13. We are symbols, and inhabit symbols : a script that creates symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14. Copy HTML files : a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
15. Let’s move : a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
16. Clean Emacs : a script that deletes all files in the current working directory that end with the character ~.
17. Tree : a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
18. Life is a series of commas, not periods : a command that lists all the files and directories of the current directory, separated by commas (,).

    *Directory names end with a slash (/)
    *Files and directories starting with a dot (.) are listed
    *The listing is alpha ordered, except for the directories . and .. is listed at the very beginning
    *Only digits and letters are used to sort; Digits should come first
    *The listing end with a new line
