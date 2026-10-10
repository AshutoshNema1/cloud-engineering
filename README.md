# Cloud Engineering — 90 Day Journey

A hands-on learning journey covering Linux, Cloud Engineering, Data Engineering, and DevOps.

---

## Day 1 — Linux Foundations

### Environment
- Windows 11
- Ubuntu running through WSL2

### Topics Learned
- `pwd` — Display the current working directory
- `ls` — List files and directories
- `ls -a` — Display hidden files and directories
- `ls -l` — Display detailed file information
- `ls -lah` — Display detailed information in a human-readable format, including hidden files
- `cd` — Navigate directories
- `mkdir` — Create directories
- `touch` — Create empty files
- `cp` — Copy files and directories
- `mv` — Move or rename files and directories
- `rm` — Remove files and directories
- Absolute and relative paths
- Linux filesystem layout
- Basic Git setup and repository workflow

### Linux Filesystem
- `/` — Root of the filesystem
- `/home` — User home directories
- `/etc` — Configuration files
- `/var` — Variable data and logs
- `/tmp` — Temporary files
- `/usr` — Programs and shared resources
- `/mnt` — Mounted filesystems, including Windows drives in WSL

### Git
- Initialized a Git repository
- Configured Git identity
- Learned about the working tree, staging area, and commits
- Connected the local repository to GitHub
- Practiced committing and pushing changes

---

## Day 2 — Linux Files, Text Processing, and Permissions

### File Viewing
- `cat` — Display file contents
- `cat -n` — Display file contents with line numbers
- `less` — Read files page by page
- `head` — Display the beginning of a file
- `tail` — Display the end of a file
- `tail -f` — Follow new lines added to a file, useful for monitoring logs

### Finding Files and Searching Text
- `find` — Search for files and directories
- `find -name` — Find entries matching a filename pattern
- `find -type f` — Find regular files
- `find -type d` — Find directories
- `grep` — Search for matching text
- `grep -n` — Display matching lines with line numbers
- `grep -i` — Search without case sensitivity
- `grep -v` — Display lines that do not match
- `grep -r` — Search recursively through directories

### Sorting and Text Processing
- `sort` — Sort lines of text
- `sort -r` — Sort lines in reverse order
- `uniq` — Remove adjacent duplicate lines
- `uniq -c` — Count adjacent occurrences of lines
- `cut` — Extract selected fields from lines
- `cut -d: -f1` — Extract the first field using a colon delimiter
- Pipes (`|`) — Pass one command's output to another command

### Input and Output Redirection
- `>` — Redirect output to a file, overwriting existing contents
- `>>` — Append output to a file
- `<` — Redirect a file's contents to standard input
- `wc -l` — Count lines in a file or input

### File Permissions and Ownership
- `ls -l` — Inspect file permissions and ownership
- `chmod` — Change file or directory permissions
- Symbolic permissions using `u`, `g`, and `o`
- Permission operators: `+`, `-`, and `=`
- Numeric permissions using `r = 4`, `w = 2`, and `x = 1`
- Common permission modes: `644`, `600`, and `755`
- Directory permissions and the role of read, write, and execute
- `chown` — Change file ownership and group
- `sudo` — Run commands with elevated privileges when authorized

### Hands-on Practice
- Created and searched text and log files
- Used `find` and `grep` to locate files and search their contents
- Sorted text and removed duplicate entries
- Counted duplicate lines using `uniq -c`
- Extracted fields from colon-separated data using `cut`
- Practiced pipes and input/output redirection
- Changed file and directory permissions
- Changed ownership of a practice file to `root` and restored it to the original user
- Compared `whoami` with `sudo whoami`
- Documented commands and explanations in a separate notes file

### Day 2 Notes
See [day02/notes.txt](day02/notes.txt) for command examples and explanations.

---

## Learning Approach
- Learn concepts and understand command syntax
- Practice commands in Ubuntu through WSL2
- Document important lessons
- Track progress with Git and GitHub
- Commit completed work regularly
