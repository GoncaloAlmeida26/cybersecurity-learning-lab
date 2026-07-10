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
