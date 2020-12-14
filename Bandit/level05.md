`ssh -p 2220 bandit5@bandit.labs.overthewire.org`  
password: `koReBOKuIDDepwhWk7jZC0RTdopnAYKh`  

```bash
bandit5@bandit:~$ find . -type f -size 1033c ! -executable -exec file {} + | grep ASCII
./inhere/maybehere07/.file2: ASCII text, with very long lines
bandit5@bandit:~$ cat ./inhere/maybehere07/.file2 | egrep "[a-zA-Z0-9]+"
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```

