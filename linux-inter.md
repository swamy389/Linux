windows vs linux 
---------------------------------
less cost 
more performance
more stability 
free OS
security

Linux server ---> everything is text

flavour distributions
---------------------------

kernel + shell + utilities = Distributions

Ubuntu ----> community OS
centOs
Fedore
RHEL ----> Enterprise OS = you will get support
Suse
Arch linux


public key/private key mechanism

ssh --> secure shell protocol

protocol port-no IP-Address username password/privatekey

HTTP 80
MYSQL 3306
DNS 53
SMTP 25
tomact 8080


how to create public/private key-pair
-------------------------------------

ssh-keygen -f <file name>

how to connect linux server
---------------------------------

ssh -i devops.pem (path for publicpublic/private key-pair) username@Public-key

ssh -i devops.pem ec2-user@52.23.200.107

$ --> indicates normal user 
# --> indicates root user

1) what is the differnce b/w wget & wget curl?
wget <url> --> it is used to download the files into linux server
wget curl <url>  ---> it is used to show the content(instead of downloading) in terminal

2)what is the difference b/w cut & awk commands?
cut ---> cut and awk we can use it for the delimitation purpose you can choose any delimiter and cut the text but awk has another usage i.e column based
 
cut ----> cut -d / -f1
awk ----> awk -F / '{print $1F}'

3)how to change ownership in linux?
the command is chown and we have root access otherwise we don't
chown <user-name>:<group-name> -R <folder or file-name>

4)there is running a lot of processes how can you search for java process?
the command is ps -ef | grep 

5)what is inode?
inode is the pointer location inside the harddisk of linux file and folder

6)what is softlink or semlink or symbalink and hardlink?
ln -s <source-file> (/home/ec2-user) <link-file-name> ---> creating softlink
ln <source-file> (/home/ec2-user) <link-file-name> ---> creating hardlink

softlink inode is different but hardlink inode is same as the source file
if you delete the source file you can not open the soft link but you still open 
the hardlink.

7)what is the difference b/w forward proxy and reverse proxy?
answer in the blow link
https://github.com/sivadevopsdaws74s/roboshop-documentation/blob/master/nginx.MD

linux
--------------------------------
96.4% of world servers are linux servers

what is server?
server is an electric device it has below characteristics
server is only one purpose i.e. host the application.

OS
RAM 
CPU/Processor
HD(hard disk)



