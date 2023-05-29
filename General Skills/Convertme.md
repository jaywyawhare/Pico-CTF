# Convertme.py

## Overview :

* General Skills
* 100 Points

## Description :

Run the Python script and convert the given number from decimal to binary to get the flag.
[Download Python script](https://artifacts.picoctf.net/c/31/convertme.py)

## Hints :

1. Look up a decimal to binary number conversion app on the web or use your computer's calculator!
1. The str_xor function does not need to be reverse engineered for this challenge.
1. If you have Python on your computer, you can download the script normally and run it. Otherwise, use the wget command in the webshell.
1. To use wget in the webshell, first right click on the download link and select 'Copy Link' or 'Copy Link Address'
1. Type everything after the dollar sign in the webshell: $ wget , then paste the link after the space after wget and press enter. This will download the script for you in the webshell so you can run it!
1. Finally, to run the script, type everything after the dollar sign and then press enter: 
    ```bash
    $ python3 convertme.py
    ```

## Approach :

```bash
$ chmod +x convertme.py
$ python3 ./convertme.py
```

## Flag : 

**picoCTF{4ll_y0ur_b4535_9c3b7d4d}**