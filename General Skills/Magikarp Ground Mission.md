# Magikarp Ground Mission

## Overview :

* General Skills
* 30 Points

## Description :

Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `6d448c9c`

## Hints :

* Finding a cheatsheet for bash would be really helpful!

## Approach :
```bash
$ ssh ctf-player@venus.picoctf.net -p 49219
$ cat 1of3.flag.txt
```

```bash
$ cat instructions-to-2of3.txt 
$ cd /
$ cat 2of3.flag.txt
```
```bash
$ cat instructions-to-3of3.txt 
$ cd ~
$ cat 3of3.flag.txt 
```

## Flag : 

**picoCTF{xxsh_0ut_0f_\/\/4t3r_5190b070}**
