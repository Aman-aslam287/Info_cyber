# LINUX COMMANDS
# 1) Package Management (Debian-based)
|Command      |Description       |Example
|-------------|------------------|-----------------------
|`apt update` | Update repo info | `sudo apt update`
|`apt upgrade`| Upgrade packages | `sudo apt upgrade`
|`apt install`| Install a package| `sudo aptt install nmap`
|`apt remove` | Remove a package | `sudo apt remove apache2`

# 2) File & Directory Commands
|Command  |Description              |Example                     |
|---------|-------------------------|----------------------------|
|`pwd`    | Show cuurent directory  | `pwd`                      |
|`ls`     | List files/directories  | `ls-l`                     | 
|`ls-l`   | Detailed listing        | `ls-l`                     |
| `ls-a`  | Show hidden files       | `ls-a`                     |
| `cd`    | Change directory        | `cd/etc`                   |
| `cd  ..`| Go up one level         | `cd  ~`                    | 
| `cd  -` | Go to previous directory| `cd  -`                    |
| `mkdir` | Create Directory        | `mkdir testdir`            |
| `rmdir` | Remove empty directory  | `rmdir testdir`            |
| `rm`    | Remove files/directories| `rm file.txt`, `rm -r dir/`|
| `touch` | Create empty file       | `touch file1.txt`          |
| `cp`    | Copy file/directory     | `cp file1.txt file1.txt`   |
| `mv`    | Move/remove file        | `mv file1.txt file2.txt`   |
| `find`  | Search for files        | `find . -name "*.sh"`      |


# 3) File Conent Commands
|Command         |Description                    |Example
|----------------|-------------------------------|-----------------
| `cat`          | View file content             | `cat file.txt`
| `more` , `less`| View file with scroll         | `less file.txt`
| `head`         | View first 10 lines           | `head file.txt`
| `tail`         | View last 10 lines            | `tail file.txt`
| `wc`           | Word/line count               | `wc -1 file.txt`
| `cut`          | Extract columns               | `cur -d',' -f1 file.csv`
| `sort`         | Sort file lines               | `sort file.txt`
| `uniq`         | Remove duplicates             | `uniq file.txt`
| `diff`         | Show differences between files| `diff file1 file2`



# 4) User & Permissions
|Command         |Description   |Example
|----------|--------------------|-----------------
| `whoami` | Show current user  | `whoami`
| `id`     | Show user group IDs| `id`
| `chmod`  | Change permissions | `chmod 755 script.sh`
| `chown`  | Change owner       | `chown root:root file.txt`
| `adduser`| Add user           | `adduser alice`
| `passwd` | Change passwords   | `passwd alice`
| `su`     | Switch user        | `su -`
| `sudo`   | Run as superuser   | `sudo apt update`

# 5) Netwoking
|Command             |Description                |Example                          |
|--------------------|---------------------------|---------------------------------|
| `ping`             | Test connectivity         | `ping google.com`               |
| `ifconfig` / `ip a`| View network interferfaces| `ip a`                          |
| `netstat -tuln`    | View open ports           | `netstat -tuln`                 |
| `curl`             | Fetch URLs                | `curl http://example.com`       |
| `wget`             | Download files            | `wget https://file.com/file.txt`|


# 6) File Compression $ Archiving 
|Command     |Description         |Example
|------------|--------------------|------------------------------
| `tar`      | Archive files      | `tar -cvf archive.tar file1 file2`
| `tar -xvf` | Extract tar archive| `tar -xvf archive.tar`
| `tar -czvf`| Create gzip tar    | `tar -czvf archive.tar.gz dir/`
| `gzip`     | Compress file      | `gzip file.txt`
| `gunzip`   | Decompress ` .gz`  | `gunzip file.txt.gz`
| `zip`      | Zip files          | `zip archive.zip file1 file2`
| `unzip`    | Unzip archive      | `unzip archive.zip`
