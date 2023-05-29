# Let's Warm Up 

## Overview :

* General Skills
* 50 Points 

## Description :

If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?

## Hint :

* Submit your answer in our flag format. For example, if your answer was 'hello', you would submit 'picoCTF{hello}' as the flag.

## Approach :

```bash
$ echo "obase=10;ibase=70;3D" | bc  
```

*112 = p in ascii* 

## Flag : 

**picoCTF{p}**
