# Fixme2.py

## Overview :

* General Skills
* 100 Points

## Description :

Fix the syntax error in the Python script to print the flag.
[Download Python script](https://artifacts.picoctf.net/c/65/fixme2.py)

## Hints :

1. Are equality and assignment the same symbol?

1. To view the file in the webshell, do: 
    ```bash
    $ nano fixme2.py
    ```

1. To exit nano, press Ctrl and x and follow the on-screen prompts.

1. The str_xor function does not need to be reverse engineered for this challenge.

 

## Approach :

Syntax error in Line 22.
(Replace = with == )

```bash
$ chmod +x fixme2.py
$ python3 ./fixme2.py
```

## Flag : 

**picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}**

