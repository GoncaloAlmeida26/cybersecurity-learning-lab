# Linux Basics

These are my notes while learning Linux fundamentals for cybersecurity, networking and system administration.

## Why Linux matters for cybersecurity

Linux is widely used in servers, networking, cybersecurity tools and penetration testing environments.

Learning Linux helps me understand:

- How operating systems manage files and permissions
- How to use the terminal effectively
- How services and processes work
- How logs are stored and analyzed
- How many cybersecurity tools are installed and used

## Basic Commands

```bash
pwd
ls
cd
mkdir
touch
cp
mv
rm
cat
less
clear
```

## Files and Directories

Common Linux directories:

- `/home` - user files
- `/etc` - configuration files
- `/var` - logs and variable data
- `/bin` - essential commands
- `/usr` - user programs and libraries
- `/tmp` - temporary files

## Permissions

Linux permissions control who can read, write or execute a file.

Basic permission types:

- `r` - read
- `w` - write
- `x` - execute

User categories:

- user
- group
- others

Example:

```bash
ls -l
chmod +x script.sh
```

## Networking Commands

```bash
ip addr
ping example.com
traceroute example.com
ss -tuln
curl example.com
```

## Notes

I will keep improving this file as I learn Linux through practice.

## Practice Log - Linux Terminal Basics

Date: 2026-09-15

### What I Practiced

- Checking the current directory
- Listing files and folders
- Creating directories
- Moving between directories
- Creating a text file
- Writing text into a file
- Reading file contents
- Copying a file
- Renaming a file

### Commands Used

```bash
pwd
ls
mkdir
cd
touch
echo
cat
cp
mv
```

### Mistake I Made

I tried to use `..` as a command.

I learned that `..` represents the parent directory, but it must be used with a command such as:

```bash
cd ..
```

### What I Learned

- `pwd` shows the current directory.
- `ls` lists files and folders.
- `mkdir` creates directories.
- `cd` changes the current directory.
- `touch` creates an empty file.
- `echo` can write text into a file using `>`.
- `cat` displays the contents of a file.
- `cp` copies files.
- `mv` moves or renames files.

### What I Need to Review

- Relative and absolute paths
- File permissions
- Safe use of commands like `rm`
