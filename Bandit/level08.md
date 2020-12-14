`ssh -p 2220 bandit8@bandit.labs.overthewire.org`  
password: `cvX2JJa4CFALtqS87jk27qwqGhBM9plV`  

```bash
bandit8@bandit:~$ strings=$(cat data.txt | sort |   uniq)
bandit8@bandit:~$ for f in $strings; do nums=$(egrep -c $f data.txt );if [ $nums == 1 ] ; then  echo $f ; fi ; done
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```
