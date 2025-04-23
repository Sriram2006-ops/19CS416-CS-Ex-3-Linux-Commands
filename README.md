# 19CS416-CS-Ex-3-Linux-Commands

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**
![image](https://github.com/user-attachments/assets/3e6987b5-bf22-43f8-a048-57a7fd8488fa)

### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
![image](https://github.com/user-attachments/assets/2da7fae9-734c-4c90-aa07-21b826142b22)

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/87289925-418d-403a-ad21-433c2d7caaf2)

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/1a6f735b-e4dd-49d9-b6e9-350c542adc5d)

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/cdb16d93-7db3-4669-8163-77f20645178d)

### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
![image](https://github.com/user-attachments/assets/57d1ca06-009c-4df9-a609-3bd9b3aa2d12)

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
![image](https://github.com/user-attachments/assets/32cef844-47de-4cc8-9e23-4d0a8a734d5f)

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/e34777c5-1276-4c35-aff7-3fe60807c641)

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
![image](https://github.com/user-attachments/assets/b2727936-a17f-4372-89cd-b5d24cfa1cac)

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
![image](https://github.com/user-attachments/assets/94294518-7279-4d6e-9d56-ee2f779cf7e0)

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
![image](https://github.com/user-attachments/assets/097652a7-810f-41d6-8900-8f1e6d9edef0)

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/65b0661c-e357-44dd-a229-75e2ad5236b1)

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/f8e0cc09-d45e-42b6-bc1c-192d931e02bf)

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
![image](https://github.com/user-attachments/assets/8b544365-7ae7-4d3c-92e6-80a4d19e8c02)

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
![image](https://github.com/user-attachments/assets/e33cf54e-1189-4726-a133-2664bb787c8e)

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
command | tr <old> <new>
echo "hello world" | tr 'a-z' 'A-Z'
echo "banana" | tr -d 'a'
echo "one two three" | tr ' ' '\n'
### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/d90119e5-d7a2-4b4e-9cf5-5af96cdae431)

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
![image](https://github.com/user-attachments/assets/b646ced0-0405-417a-aacd-e688e48b9acd)

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/2548e77c-ebd4-48b3-93c0-b57b680790ad)

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
![image](https://github.com/user-attachments/assets/1c07e265-b6c4-40e7-b706-cee4d93b5a6b)

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
![image](https://github.com/user-attachments/assets/1c355f8b-6149-45ea-b53f-3e7393ebf800)

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
![image](https://github.com/user-attachments/assets/0c063fe3-3e65-4cb7-b5b8-4a8c89889682)

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
![image](https://github.com/user-attachments/assets/5eac3bcb-5a6f-4c82-8c5d-3e67c5af5e46)

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
![image](https://github.com/user-attachments/assets/d0601044-0595-4c7a-aafa-477538c950eb)

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/7947acca-dd27-48d3-8e49-5fa7c82ab4c9)

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
![image](https://github.com/user-attachments/assets/ac92330d-2315-4e26-9ffc-ac804defc345)


### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
![image](https://github.com/user-attachments/assets/66a10468-554e-4fb2-9a15-240adcfeee06)

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
![image](https://github.com/user-attachments/assets/87a7aac7-8400-4990-ba55-c6621af1b940)

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
![image](https://github.com/user-attachments/assets/95e31516-0f21-4fdc-815d-47e860c9ffbf)

### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
![image](https://github.com/user-attachments/assets/fc96aef7-a94d-4323-ab4d-2ed3f63367fd)

## Result
