# **Linux Command Cheat Sheet**
| Category | Command | Description | Options | Examples |
|---------|---------|-------------|---------|----------|
| File and Directory Operations | `ls`    | List files and directories.  | `-l`: Long format listing.<br>`-a`: Include hidden files.<br>`-h`: Human-readable file sizes. | `ls -l` → displays files and directories with detailed information.<br>`ls -a` → shows all files and directories, including hidden ones.<br>`ls -lh` → displays file sizes in a human-readable format. |
|         | `cd`    | Change directory. |         | `cd /path/to/directory` → changes the current directory to the specified path. |
|         | `pwd`   | Print current working directory. |         | `pwd` → displays the current working directory. |
|         | `mkdir` | Create a new directory. |         | `mkdir my_directory` → creates a new directory named "my_directory". |
|         | `rm`    | Remove files and directories. | `-r`: Remove directories recursively.<br>`-f`: Force removal without confirmation. | `rm file.txt` → deletes the file named "file.txt".<br>`rm -r my_directory` → deletes the directory "my_directory" and its contents.<br>`rm -f file.txt` → forcefully deletes the file "file.txt" without confirmation. |
|         | `cp`    | Copy files and directories. | `-r`: Copy directories recursively. | `cp -r directory destination` → copies the directory "directory" and its contents to the specified destination.<br>`cp file.txt destination` → copies the file "file.txt" to the specified destination. |
|         | `mv`    | Move/rename files and directories. |         | `mv file.txt new_name.txt` → renames the file "file.txt" to "new_name.txt".<br>`mv file.txt directory` → moves the file "file.txt" to the specified directory. |
|         | `touch` | Create an empty file or update file timestamps. |         | `touch file.txt` → creates an empty file named "file.txt". |
|         | `cat`   | View the contents of a file. |         | `cat file.txt` → displays the contents of the file "file.txt". |
|         | `find`  | Search for files and directories. | `-name`: Search by filename.<br>`-type`: Search by file type. | `find /path/to/search -name "*.txt"` → searches for all files with the extension ".txt" in the specified directory. |
| File Permissions | `chown`  | Change file ownership. |         | `chown user file.txt` → changes the owner of "file.txt" to the specified user. |
|         | `chgrp`  | Change group ownership. |         | `chgrp group file.txt` → changes the group ownership of "file.txt" to the specified group. |
|         | `umask`  | Set default file permissions. |         | `umask 022` → sets the default file permissions to read and write for the owner, and read-only for group and others. |

# **Git Command Cheat Sheet**
| Category | Command | Description |
|----------|---------|-------------|
| Setup | `git config --global`.<br>`user.name "firstname lastname"` | set a name that is identifiable for credit when review version history |
|       | `git config --global`.<br>`user.email "valid-email"` | set an email address that will be associated with each histroy marker |
|       | `git config --global`.<br>`color.ui auto` | set automatic command line coloring for Git for easy reviewing |









