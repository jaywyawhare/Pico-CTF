# Python Wrangling

## Overview :

* General Skills
* 10 Points

## Description :

Python scripts are invoked kind of like programs in the Terminal... Can you run this Python script using this password to get the flag?

## Hint :

1. Get the Python script accessible in your shell by entering the following command in the Terminal prompt: 
    ```bash
    $ wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py 
    ```

1.  ```bash
    $ man python
    ``` 


## Approach :

```bash
    $ cat pw.txt
```
Password = aa821c16aa821c16aa821c16aa821c16

```bash
    $ python3 ./ende.py -d flag.txt.en
```

## Flag : 

**picoCTF{4p0110_1n_7h3_h0us3_aa821c16}**
