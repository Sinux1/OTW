`ssh -p 2220 bandit4@bandit.labs.overthewire.org`  
password: `pIwrPrtPN36QITSp3EQaw936yaFoFgAB`  

```
bandit4@bandit:~$ find ./inhere -type f -exec file {} + | grep ASCII
./inhere/-file07: ASCII text
bandit4@bandit:~$ cat ./inhere/-file07 
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
```
