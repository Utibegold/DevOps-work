
# LAMP STACK IMPLEMENTATION

## Whats is Lamp stack?
The `Lamp stack` is a popular open-source software bundle used for web development. It stands for Linux (operating system), Apache (web server), MySQL (database), and PHP (programming language). Its a robust combination for creating dynamic websites and web applications.



The goal of implementing the `lamp stack` is to understand and create a powerful and dynamic environment for web development.


## STEPS FOR THE IMPLEMENTATION 

- AWS sign up
- Created an EC2 instance (Elastic Compute Cloud)
- ssh to the server through the terminal
- Installing Apache2
- Installing Mysql
- Installing PHP
- Enable PHP on the website

## Connecting to EC2:
![Ec2](./images/lamp%20p.%201.png)

- EC2 is the foundamental part of AWS taht provides the infrastructure for computing resources in the cloud. the screenshot shows the the instace is active and running in the server.

## Sudo Apt Update
- This is the first to do when working or installing an apt, it is standard way of getting started to confirm the status of the system. below is the screenshot tht confirms the status of the apt.

![sudo apt](./images/sudo%20apt.upd.%202.png)


This screenshot to confirm the cofirmation that Apache2 has been installed and running in the ubuntu server.

![apa int](./images/inst.apache.%203.png)

## Systemctl
$ sudo systemctl status apache2

- This is to check the status of the system,this commandline are executed with administrative privileges and can control the behavior of services  within the system. 
 ![systemctl](./images/systemctl.%204.png)


$ curl http://localhost:80
or
$ curl http://127.0.0.1:80

 ![port 80](./images/port%2080.%205.png)
 
 Port 80 is a well-known port number used for internet communication, Its the default port for `Hypertext Transfer Protocol`traffic which is commonly used for accessing websites. the screenshot is to show the connection to the port 80.


 ![curl](./images/curl.%20http.6.png)

 
 This curl command is a versatile command-line tool used to transfer data to or from a server.it supports different protocol. I used this to request apache Http server on port 80. it can also achieve the same aim even when you dont specify port 80.

 I used the web browser to confirm my apache web browser is working.



 ![Apache](./images/apache2.%207.png)
After downloading and installing the webbrowser, and to confirm the apache2 web server, this defult page shows, meaning the its properperly installed.

 ![curl](./images/curl.%208.png)
This curl command also works for getting out IP addresses other than to check on the AWS.




![mysql](./images/inst.mysql.%209.png)

This image shows mysql has been installed. Mysql is a database managemnt system used in storing managing data on the website,it is usually relational database system used in the `php environments`


![sudomysql](./images/inst%20mysql%209b.png)

This command will connect to the system as the root system administrator, meaning someone with priviledges to work in the system

![sudo](./images/sudo%20mysql%2010.png)


![mysql p](./images/mysql%20inst.%2011.png)

This command will ask for password validation during mysql installation. the screenshot shows the successful installation of the databased management system. and this command can only be perform by the administrator with root priviledge.


![](./images/mysql%20pas%20val.12.png)
This command ask if you want to confiqure or validate the password, and by chosing Yes, itll take you to the validating processes. which will confirm the password set with certain criteria.

![](./images/pass%20val.%2013.png)
After folowing all the due processes in setting up the server, youll receive the message all done, meaning it was succesfully installed.


![sudo mysql -p](./images/mysql%20-p%2014.png)
This command activates password entry to the system for access control, note that if the wrong password is inputed, itll automatically reject it.




![sudo php](./images/php%20apac%2015.png)
PHP is a language that will process code to show the dynamic content to end users. the screenshot shows the installation was succesful and working properly


![](./images/php%20apa%2015a.png)

![](./images/php%20-v%2016.png)

The php -v command is used to cinfirm the version of the php installed in the system.

![](./images/a2ensit%2017..png)

![](./images/php%20info.%2018.png) 

The picture of the version of PHP as shown.


