# Information

## Overview :

* Forensics
* 10 Points

## Description :

Files can always be changed in a secret way. Can you find the flag? [cat.jpg](mercury.picoctf.net/static/b4d62f6e431dc8e563309ea8c33a06b3/cat.jpg)

## Hints :

1. Look at the details of the file

1. Make sure to submit the flag as picoCTF{XXXXX} 

## Approach :

```bash
$ exiftool cat.jpg
```

Licence Key = cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9

```bash
$ echo cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9 | base64 -d
```

## Flag : 

**picoCTF{the_m3tadata_1s_modified}**
