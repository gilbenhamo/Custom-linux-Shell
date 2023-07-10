# Custom-linux-Shell

## Description

This project involves creating a custom shell that supports some of the original shell commands.
The purpose of this project is to gain a better understanding of how a shell operates and the logic behind processes within a real shell environment.

## Environment

- OS: Ubuntu (Linux)

### Requirements to Install

- GCC compiler
- Installation of libreadline-dev: `sudo apt-get install libreadline-dev`
- Installation of tree: `sudo apt install tree`

## How to Compile and Run

To compile:
```
gcc -o main main.c -lreadline
```

To run:
```
./main
```

To compile and run:
```
gcc -o main main.c -lreadline;./main
```

## How to Run Your Program

This program functions similar to a shell but with limited commands.

The commands supported by our custom shell include:
- pwd
- cd
- nano
- cat
- cat > \<file>
- wc (-l, -c, -w)
- cp
- pipe (command1 | command2)
- clear
- grep (-c)
- wget
- ls (-l)
- tree
- exit

### Examples

**Example (1) - Command: pwd**

```
gil : /home/gil/Desktop/hw2: >> pwd
/home/gil/Desktop/hw2
```

**Example (2) - Command: ls -l**

```
gil : /home/gil/Desktop/hw2: >> ls -l
total 40
-rw-rw-r-- 1 gil gil  6123 Apr  8 07:02 funcs.c
-rw-rw-r-- 1 gil gil   760 Apr  8 07:02 headers.h
-rwxrwxr-x 1 gil gil 18040 Apr  8 07:22 main
-rw-rw-r-- 1 gil gil  1034 Apr  8 07:02 main.c
-rw-rw-r-- 1 gil gil  1193 Apr  8 07:22 readme.txt
```

**Example (3) - Command: ls | wc -w**

```
gil : /home/gil/Desktop/hw2: >> ls | wc -w
5
```

## Author

- [Gil Ben Hamo](https://github.com/gilbenhamo)


