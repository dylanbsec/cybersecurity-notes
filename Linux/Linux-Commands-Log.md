## Entry 001 - Linux Command Review

**Date:** 7 July 2026

**Focus:** Reviewing basic Linux commands and practising in the CLI.

### Commands Practised

- `pwd` - Display the current working directory
- `ls` - List files and directories
- `cd` - Change directory
- `touch` - Create a new file
- `mkdir` - Create a new directory
- `rm` - Remove files and directories
- `cp` - Copy files and directories
- `mv` - Move or rename files and directories
- `cat` - Display the contents of a file

### Reflection

Today I reviewed Linux commands I had previously learned and practised them directly in the Athena OS terminal. This helped rebuild my confidence using the command line after taking some time away from cybersecurity.

### Next Steps

- Continue Linux practice through Pwn College.
- Learn file permissions and ownership.
- Practise commands without relying on notes.

## Entry 002 - Process Management & Secure File Transfer

**Date:** 12 July 2026

**Focus:** Learning Linux process management and secure file transfer through Hacknet.

### Commands Practised

- `ps` - Display running processes
- `kill` - Terminate a running process using its PID
- `scp` - Securely copy files between systems over SSH

### Reflection

I practised these commands while playing Hacknet. Although the environment is simulated, it provided an enjoyable way to become more comfortable using Linux commands in context rather than simply memorising them.

### Next Steps

- Continue learning Linux commands through practical use.
- Develop a better understanding of SSH and remote administration.

## Entry 003 - Multiple and Mixed Globs

**Date:** 14 July 2026

**Focus:** Using wildcard patterns to match specific groups of files in Bash.

### Commands Practised

- `*p*` - Match every filename containing the letter `p`
- `[cep]*` - Match filenames beginning with `c`, `e`, or `p`

### Reflection

I completed two pwn.college challenges covering multiple and mixed globs.

The first challenge reinforced that `*` can match any sequence of characters. I used `*p*` to select every filename containing the letter `p`.

The second challenge required combining a square bracket glob with `*` to match only `challenging`, `educational`, and `pwning`. I initially focused too much on letters shared within the filenames and overlooked the simpler pattern in their first letters.

After receiving guidance, I understood that `[cep]*` works because `[cep]` matches one starting character from the set, while `*` matches the rest of each filename.

### Next Steps

- Continue practising square bracket globs.
- Pay closer attention to simple filename patterns before testing more complicated expressions.
- Continue the pwn.college globbing module.
