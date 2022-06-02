# Nice Netcat

## Overview :

* General Skills
* 15 Points

## Description :

There is a nice program that you can talk to by using this command in a shell: 
```bash
$ nc mercury.picoctf.net 43239
```

but it doesn't speak English...

## Hints :

1. You can practice using netcat with this picoGym problem: [what's a netcat?](https://play.picoctf.org/practice/challenge/34)

1. You can practice reading and writing ASCII with this picoGym problem: [Let's Warm Up](https://play.picoctf.org/practice/challenge/22) 

## Approach :

```bash
$ nc mercury.picoctf.net 43239
```
Output = *[112, 105, 99, 111, 67, 84, 70, 123, 103, 48, 48, 100, 95, 107, 49, 116, 116, 121, 33, 95, 110, 49, 99, 51, 95, 107, 49, 116, 116, 121, 33, 95, 55, 99, 48, 56, 50, 49, 102, 53, 125, 10]*


##### Convert the given ASCII values to a string:

picoCTF{g00d_k1tty!_n1c3_k1tty!_7c0821f5}

## Flag : 

**picoCTF{g00d_k1tty!_n1c3_k1tty!_7c0821f5}**
