# 2 Warm

## Overview :

* General Skills
* 50 Points

## Description :

Can you convert the number 42 (base 10) to binary (base 2)?

## Hint :

* Submit your answer in our competition's flag format. For example, if your answer was '11111', you would submit 'picoCTF{11111}' as the flag.

## Approach :

```bash
$ echo "obase=2;42" | bc  
```

## Flag : 

**picoCTF{101010}**