`ssh -p 2220 bandit6@bandit.labs.overthewire.org`  
password: `DXjZPULLxYr17uwoI01bNLQbtFemEgo7`  

```bash
bandit6@bandit:~$ find / -size 33c -user bandit7 -group bandit6 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```

