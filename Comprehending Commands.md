## cat: not the pet, but the command!:

Execute 'cat flag'



## catting absolute paths:

Execute 'cat /flag'



## more catting practice:

Execute 'cat /lib/aspell/flag'



## grepping for a needle in a haystack:

Execute 'grep pwn.college /challenge/data.txt', which searches the 'data.txt' file for the text 'pwn.college', and prints the lines containing the expression.
grep - Global Regular Expression search and Print



## listing files:

Execute '/challenge/25653-renamed-run-479'. Here, '25653-renamed-run-479' is an executable.



## touching files:

'touch /tmp/pwn' and 'touch /tmp/college', followed by '/challenge/run'



## removing files:

'rm delete_me', followed by '/challenge/check'



## hidden files:

'ls -a /', followed by 'cat /.flag-217092655520981', where '.flag-217092655520981' was the hidden flag file.



## An Epic Filesystem Quest:

Follow the instructions, use 'ls -a' wherever necessary, either cd into the directory specified or access the files directly using absolute paths.



## making directories:

'mkdir /tmp/pwn', 'touch /tmp/pwn/college' and '/challenge/run'.



## finding files:

'find / -name flag' and then 'cat' the files found.



## linking files:

symlink '/flag' to '~/not-the-flag', and read it.
