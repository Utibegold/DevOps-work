
# LEMP STACK IMPLEMENTATION

## What is lemp stack?
The `Lemp stack` is a web development platform taht consist of `linux,Nginx Mysql and PHp`.
Its almost the same as `lamp`(linux, apache,Mysql and PHP/Python and perl). 

The goal of this project implementation is to understand and create a useful and dynamic environment for web development.

## STEPS FOR THE IMPLEMENTATION
- AWS sign up
- Created an EC2 instance (Elastic Compute Cloud)
- ssh to the server through the terminal
- Installing Nginx
- Installing Mysql
- Installing my PHP

This Lemp project is the continuation of `LAMP project `which i implemented, during the `LAMP`documntation i demonstrated with screenshot on how i signed up in the `AWS` and also how i was able to ssh to the server through the terminal.
Now im going to show the steps i took to implement the `LEMP` project. firstly, i updated the system by using `sudo apt update`code . This is a standard practice before carrying out any installation in a system.

## sudo apt update

In this implimentation of the project, i updated the apt to confirm it is upto date as seen in the screenshot below.



![apt.up](./images/apt%20up.L1.png)
In this screenshot, i demonstrated the instalation Nginx with -y which means the system should give access and accepts all the installation of the package till its completed


![inst](./images/apt%20nginx%20-y%20L2.png)

Below is the `systemctl` command line thats used to view the status of the program in the system. 


![systemctl](./images/sylts%20nginx3.png)

$ curl http://localhost:80
or
$ curl http://127.0.0.1:80



![](./images/curl%20L4.png)
![](./images/curl%20L4a.png)
The curl command was to request port 80. This command is used to transfer data to or from a server using various  protocols like HTTP,HTTPS etc.

![](./images/Ip-80%20L5.png)

![](./images/IP%20L6.png)
## ping command

This ping command is a network utiliy used to test the reahaability of a host on an internet protocol (IP)network. It sends echo request to thetarget hostand waits for echo replypackets in response.

## Installing MySql
In this installation, i used `$ sudo apt install mysql-server`
for mysql installation. i also used y when prompted to confirm the installation.

![](./images/)

![](./images/mysql%20L8a.png)

![](./images/sudo%20mysql%20L9.png)


![](./images/L10b.png)

# sudo mysql -p command
This command prompt user to input its passward in other to proceed. running sudo mysql -p in the terminal is a way to start the mysql command-line client with adminsitratibve privileges. (sudo) and prompt for the MySql root users passpword (-p).

![](./images/pass.%20L11.png)

## Configuring Nginx to use PHP procssor

![](./images/nano%20L13.png)
![](./images/nano%20L13b.png)

In this demonstration i created a web directory for a demain.

$ sudo mkdir /var/www/projectLEMP
This sudo mkdir  commands is used to create a new directory with adminsitrativeprivileges. The sudo command allows me to execute with elevated privileges.

![](./images/nano%20L13.png)
![](./images/nano%20L13b.png)

## Testing the PHP code with nginx
PHP is often used to create dynamic websites, process form date etc,itcan also be used to program application programming interfaces(API)
This creenshot shows it was properly installed during the demonstration.
![](./images/infor.php%20L14.png)


Above are screenshots demontrtions of the projects

![](./images/creat.%20L15.png)
![](./images/dat%20L16.png)


This is the successful implementation of nginx in this project.
in this implementation, i used sudo apt install nginx and sudo systemctl to be sure of the status of it. note that nginx main configuration file is usually located at the `/etc/nginx/nginx. cong`.


![](./images/L17.png![nginx](./images/Nginx%20int.L7.png)
















