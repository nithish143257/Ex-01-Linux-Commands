# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/ce708270-e777-402d-b90f-dd141bc0ef5e)

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/92cfb99c-bfd3-4045-93dd-b97271750dff)
 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/11de8555-75ab-47fe-ac5e-ae5260c14db9)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/840a8320-7b8f-4b20-987b-81979c1feb5f)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/f8f7dd3b-708d-4181-9038-7d68405c09bc)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/64885345-9f4a-45ac-8062-6e15cd3a0a2d)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/0e29133e-b951-41d1-be5b-762d546e2daf)


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/6bcc63e0-29d9-4c1b-aa45-92a94541985a)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/e2604673-0ad1-42e4-995d-8d5d6928d7db)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/1e461b7e-ca6f-4ca7-8d98-c9ffbd1af94d)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/13f0588b-dd20-49d6-a88f-a7bcf1305c1a)

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/38cf39dc-0ff3-4221-992c-ba16d1edb4c5)

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/24ae21e9-f662-4682-995c-db4b605246fd)
 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/914ce3d8-b2cb-49c1-b095-f638e250db34)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/0d072267-e980-48c4-96f0-75183a4c2126)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/6b5c0400-a046-4adb-873f-dd210c4b3864)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/cfda4ead-5c3e-4011-b2c0-f2a8017ccef5)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/3f6e69f5-c814-466c-83cd-e78232664cf7)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/988242c5-461c-4e52-9062-086e02b2f506)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/1481c059-3d04-4de3-ad8b-dcd9f8418c2b)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/8b29d45e-5b15-46b6-b976-ceb1b6cbd5d8)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/e18becdb-b637-4251-9d92-2b986c5a4329)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/21edc9d8-0ca0-4d87-bd83-a10ac21ce074)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/8e0d09d7-1f7c-4957-bc74-805aace9576f)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/f28ce148-4273-4a15-b6c9-249a46572b14)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/Dark77devil/Ex-01-Linux-Commands/assets/115543366/329485c7-1668-43ae-b4cf-8c960abb3e17)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
