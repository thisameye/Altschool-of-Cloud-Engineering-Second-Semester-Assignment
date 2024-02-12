# AltSchool  of Cloud Engineering v3 2nd Semester Assignment 2
Your login name: altschool i.e., home directory /home/altschool. The home directory contains the following sub-directories: code, tests, personal, misc Unless otherwise specified, you are running commands from the home directory.


![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707695973966_2024-02-12+00_58_40-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


a. Change directory to the tests directory using absolute pathname
`cd /home/altschool/tests`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707696073642_2024-02-12+01_00_36-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


b. Change directory to the tests directory using relative pathname
`cd tests`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707696197470_2024-02-12+01_02_49-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


c. Use echo command to create a file named fileA with text content ‘Hello A’ in the misc directory
 `echo 'Hello A' > misc/fileA`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707696359909_2024-02-12+01_05_31-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


d. Create an empty file named fileB in the misc directory
`touch misc/fileB`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707696612003_2024-02-12+01_09_06-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


e. Copy contents of fileA into fileC
`cp -n misc/fileA misc/fileC`

f. Move contents of fileB into fileD
 `mv misc/fileB misc/fileD`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707696772762_2024-02-12+01_12_17-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


 g. Create a tar archive called misc.tar for the contents of misc directory
 `tar -cvf misc.tar misc`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707697061472_2024-02-12+01_17_18-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


h. Compress the tar archive to create a misc.tar.gz file
`gzip misc.tar`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707697382446_2024-02-12+01_22_17-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


i. Create a user and force the user to change his/her password upon login
`sudo chage -d 0 example5`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707697499123_2024-02-12+01_24_24-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


j. Lock a users password
`sudo passwd -l example5`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707697593829_2024-02-12+01_26_00-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


k. Create a user with no login shell
`sudo useradd -s /sbin/nologin example6`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707697678741_2024-02-12+01_27_31-AltSchool+of+Cloud+Engineering+v3+2nd+Semester+Assignment+2++Dropbox+Paper.png)


l. Disable password based authentication for ssh
`sudo vi /etc/ssh/sshd_config`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707697755709_2024-02-12+00_48_32-Alt-School-Cloud-Assignments_Live-Class-Exercise_Cloud-Linux-Assignments+at+mast.png)


m. Disable root login
`sudo vi /etc/ssh/sshd_config`

![](https://paper-attachments.dropboxusercontent.com/s_B2BF6F62568579E185820427417EF63BD418D901F1C2D03E9144F8D263835CC8_1707697780985_2024-02-12+00_51_27-Alt-School-Cloud-Assignments_Live-Class-Exercise_Cloud-Linux-Assignments+at+mast.png)


