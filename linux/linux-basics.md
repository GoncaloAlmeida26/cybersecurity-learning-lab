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
ip route
ping -c 4 example.com
traceroute example.com
ss -tuln
curl -I https://example.com
nslookup example.com
```

## Notes

I will keep improving this file as I learn Linux through practice.

## Practice Log - Linux Fundamentals

Date: 2026-09-15

### Topics Practiced

- Terminal navigation
- File and directory creation
- Reading and writing text files
- Copying and renaming files
- Linux file permissions
- Numeric permissions with `chmod`
- Reading and searching text files
- Basic log filtering
- Processes and background jobs
- Difference between job numbers and PIDs
- Basic Linux networking commands
- DNS lookups
- HTTP response headers

### Commands Practiced

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
chmod
grep
wc
head
tail
ps
jobs
kill
ip addr
ip route
ping
ss
curl
nslookup
```

### Key Learnings

- `pwd` shows the current directory.
- `ls` lists files and folders.
- `cd ..` moves to the parent directory.
- `mkdir` creates directories.
- `touch` creates empty files.
- `echo` can write text into files.
- `cat` displays file contents.
- `cp` copies files.
- `mv` moves or renames files.
- `>` writes output to a file and replaces previous content.
- `>>` appends output to the end of a file.
- Linux permissions are divided into owner, group and others.
- `r`, `w` and `x` mean read, write and execute.
- `chmod` changes file permissions.
- Numeric permissions such as `644`, `600`, `700` and `755` are a shorter way to set permissions.
- `grep` searches for text inside files.
- `grep -n` shows line numbers.
- `grep -i` ignores uppercase and lowercase differences.
- `grep -v` excludes matching lines.
- `grep -E "ERROR|WARNING"` searches for multiple patterns.
- `wc -l` counts lines in a file.
- `head -n 2` shows the first 2 lines of a file.
- `tail -n 2` shows the last 2 lines of a file.
- `ps` shows processes.
- A PID is a process ID.
- `jobs` shows background jobs in the current shell.
- `kill %1` kills job number 1.
- `kill 2844` kills the process with PID `2844`.
- `ip addr` shows network interfaces and IP addresses.
- `ip route` shows routing information and the default gateway.
- `ping` tests connectivity.
- `ss -tuln` shows listening TCP and UDP ports.
- `nslookup` performs DNS lookups.
- `curl -I` shows HTTP response headers.


### Shell Operators

- `|` sends the output of one command into another command.
- Inside `grep -E`, `|` can mean "or", for example `ERROR|WARNING`.
- `||` runs the second command only if the first command fails.
- `;` runs commands one after another.
- `&&` runs the second command only if the first command succeeds.

### Security Notes

- Logs can be filtered to find important events such as failed logins, permission errors and references to privileged users.
- Searching for keywords like `failed`, `denied`, `root`, `ERROR` and `WARNING` can help identify suspicious activity.
- Open/listening ports are important because they show services that may be reachable.
- HTTP response headers can reveal useful security-related information.
- Public writeups should avoid pasting full cookie values or sensitive output.
