```bash

ssh bandit6@bandit.labs.overthewire.org -p 2220
$ls -a
$cd ./..
/home$ ls -a
/home$ find / -type f -user bandit7 -group bandit6 -size 33c
/home$ cat /var/lib/dpkg/info/bandit7.password
Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3  #PASSWD
$logout
```

[LVL 7-8](LVL%207-8.md)
