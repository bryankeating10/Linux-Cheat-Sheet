# **Linux Command Cheat Sheet**
| Command | Description | Options | Examples |
|---------|-------------|---------|----------|
| `ls`    | List files and directories.  | `-l`: Long format listing.<br>`-a`: Include hidden files.<br>`-h`: Human-readable file sizes. | `ls -l` → displays files and directories with detailed information.<br>`ls -a` → shows all files and directories, including hidden ones.<br>`ls -lh` → displays file sizes in a human-readable format. |

# **Git Command Cheat Sheet**
| Category | Command | Description |
|----------|---------|-------------|
|         | `chmod` | Change file permissions. | `u`: User/owner permissions.<br>`g`: Group permissions.<br>`o`: Other permissions.<br>`+`: Add permissions.<br>`-`: Remove permissions.<br>`=`: Set permissions explicitly. | `chmod u+rwx file.txt` → grants read, write, and execute permissions to the owner of the file. |
|         | `chown`  | Change file ownership. |         | `chown user file.txt` → changes the owner of "file.txt" to the specified user. |
|         | `chgrp`  | Change group ownership. |         | `chgrp group file.txt` → changes the group ownership of "file.txt" to the specified group. |
|         | `umask`  | Set default file permissions. |         | `umask 022` → sets the default file permissions to read and write for the owner, and read-only for group and others. |
