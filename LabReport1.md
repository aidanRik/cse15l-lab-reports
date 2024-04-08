# Blog Post 1
> ## Aidan Rikic
---
1. cd
* cd with no arguments
```
aidan_rikic@Aidans-MacBook-Air lecture1 % cd
aidan_rikic@Aidans-MacBook-Air ~ % 
```
Prior Absolute path: /Users/aidan_rikic/lecture1
The output shows the tilde because using 'cd' with no argument sets the working directory to HOME if the variable exists.

* cd with *directory*
```
aidan_rikic@Aidans-MacBook-Air lecture1 % cd messages 
aidan_rikic@Aidans-MacBook-Air messages %
```
Prior Absolute path: /Users/aidan_rikic/lecture1
The output showcases the current working directory, which in this case will be 'messages'. This is not an error as the directory 'messages' is within 'lecture1'.

* cd with *file*
```
aidan_rikic@Aidans-MacBook-Air messages % cd en-us.txt
cd: not a directory: en-us.txt
```
Prior Absolute path: /Users/aidan_rikic/lecture1/messages
The output is an error because we tried calling a file using 'cd' which is calling the current directory. 

2. ls 
* ls with no arguments
```
aidan_rikic@Aidans-MacBook-Air lecture1 % ls
Hello.class     Hello.java      README          messages
```
Prior absolute path: /Users/aidan_rikic/lecture1 
The output is a list of all the directories under the current directory, in this case 'lecture1'. This is not an error. 

* ls with *directory*
```
aidan_rikic@Aidans-MacBook-Air lecture1 % ls messages 
Serbian-sr.txt  en-us.txt       es-mx.txt       zh-cn.txt
```
Prior absolute path: /Users/aidan_rikic/lecture1
The output is a list of all the files within the directory we used as the argument. This is not an error as it just prints the file names.

* ls with *file*
```
aidan_rikic@Aidans-MacBook-Air messages % ls en-us.txt
en-us.txt
```
Prior absolute path: /Users/aidan_rikic/lecture1/messages
The output just lists the file that I used as the argument. This is not an error, but say I called 'ls en-us.txt' when I was currently in the 'lecture1' directory then it would return an error, this is because the file 'en-us.txt' is within 'messages' and not 'lecture1'. 

3. cat 
*
