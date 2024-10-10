## Resources:

https://web.archive.org/web/20220629044814/http://bencane.com:80/2012/04/16/unix-shell-the-art-of-io-redirection/

http://www.rozmichelle.com/pipes-forks-dups/



## Redirecting output:

Execute 'echo PWN > COLLEGE'.



## Redirecting more output:

Execute '/challenge/run > myflag', followed by 'cat myflag'.



## Appending output:

Execute '/challenge/run >> /home/hacker/the-flag' twice, followed by 'cat /home/hacker/the-flag'.



## Redirecting errors:

Execute '/challenge/run > myflag 2> instructions', followed by 'cat myflag'.



## Redirecting input:

Execute 'echo COLLEGE > PWN', followed by '/challenge/run < PWN'.



## Grepping stored results:

Execute '/challenge/run > /tmp/data.txt', followed by 'grep pwn.college /tmp/data.txt'.



## Grepping live output:

Execute '/challenge/run | grep pwn.college'



## Grepping errors:

Execute '/challenge/run 2>& 1 | grep pwn.college'



## Duplicating piped data with tee:

Execute '/challenge/pwn | tee test | /challenge/college', cat the 'test' file to get the secret code. Finally execute '/challenge/pwn --secret [code] | /challenge/college' to get the flag.



## Writing to multiple programs:

Execute '/challenge/hack | tee >(/challenge/the) | tee >(/challenge/planet)'.



## Split-piping stderr and stdout:

Execute '/challenge/hack > >( /challenge/planet ) 2> >( /challenge/the )'.
