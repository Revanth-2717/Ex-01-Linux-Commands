# Ex-01-Linux-Commands
`
Name: REVANTH.P
`
`
Reg No: 212223040143
`

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
![IS COMMAND](https://github.com/user-attachments/assets/74d903b0-69ff-4007-a338-8b9357b4d340)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![PWD](https://github.com/user-attachments/assets/942f7c6f-866f-4606-9523-f8668ad5d1a4)

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir 
![MKDIR](https://github.com/user-attachments/assets/fe509c63-2c75-4655-9e1a-ca6f286c56f9)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![RMDIR](https://github.com/user-attachments/assets/065d9955-22d9-407d-b1b4-6e4dbf4b29a7)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![CD](https://github.com/user-attachments/assets/e217b4fa-a77c-4e29-82d0-ea7e6eafd335)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![CAT](https://github.com/user-attachments/assets/a82b7dfd-c342-4ae6-abf3-48bc283517c3)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![cp](https://github.com/user-attachments/assets/f28da59b-c2f5-45e5-bed5-bb688b2c39f5)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![gedit](https://github.com/user-attachments/assets/f15a634c-8531-4f7a-becb-80ecaddc1242)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![su](https://github.com/user-attachments/assets/f8092d13-e3af-4035-9a2f-556918a7e4b3)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![mv](https://github.com/user-attachments/assets/b91d4d37-d873-44a3-98c5-9f9c7e3dc29e)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![rename](https://github.com/user-attachments/assets/6ec7beb1-d45f-4e61-8939-bc32b74fbcfe)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![head](https://github.com/user-attachments/assets/d995631e-2ce7-4f3e-be0d-ad48a946a8d9)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![tail](https://github.com/user-attachments/assets/099d6776-ebd9-436a-a126-b1ef91d631ce)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![id](https://github.com/user-attachments/assets/096a6727-50c7-4aed-a81f-51eaec36e069)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
![grep](https://github.com/user-attachments/assets/b0bfa946-4809-4683-b05e-e83386f67027)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![tr](https://github.com/user-attachments/assets/4eb6663c-55b7-4659-9499-0cfe4993efea)

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
![chown](https://github.com/user-attachments/assets/3ed63885-eaf1-4fad-8044-7a51032b5f8f)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![make](https://github.com/user-attachments/assets/e458a201-76da-471a-a7b7-79080587f5bb)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![ifconfig](https://github.com/user-attachments/assets/9ba8270e-490d-4e13-a566-a2cef097c125)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![host](https://github.com/user-attachments/assets/e0ed9dce-084c-4086-8b0d-164b29eda003)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![gzip](https://github.com/user-attachments/assets/32474ce1-1bb4-4600-9071-92ac70004cfe)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![sort](https://github.com/user-attachments/assets/7020b0fb-4b8d-4e07-a3c9-7feb6d3644a5)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![cal](https://github.com/user-attachments/assets/232f3447-af79-4f61-9f76-29ef4abae062)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![clear](https://github.com/user-attachments/assets/49fd5d0f-efb4-434c-b446-cc219e5cebc7)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 ![mail](https://github.com/user-attachments/assets/c6faef68-0a3e-498a-946d-153392d36256)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![df](https://github.com/user-attachments/assets/a14bcc9a-4e86-4377-acd1-c0e47a0dd093)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu
