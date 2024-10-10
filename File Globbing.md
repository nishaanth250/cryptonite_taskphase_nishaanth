## Resources:

https://www.gnu.org/software/bash/manual/html_node/Shell-Expansions.html



## Matching with *:

Execute 'cd /c*e', followed by './run'.



## Matching with ?:

Execute 'cd /?ha??enge', followed by './run'.



## Matching with []:

Execute 'cd /challenge/files', followed by '/challenge/run file_[bash]'.



## Matching paths with []:

Execute '/challenge/run /challenge/files/file_[bash]'.



## Mixing globs:

Execute 'cd /challenge/files', followed by '/challenge/run [cep]*'.



## Exclusionary globbing:

Execute 'cd /challenge/files', followed by '/challenge/run [!pwn]*'.
