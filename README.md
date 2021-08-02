# VPLE 
![](https://github.com/Adityaraj6/VPLE/blob/main/VPLE.png)
<img src="https://github.com/Adityaraj6/VPLE/blob/main/VPLE.png" width="100" height="100">

## Vulnerable Pentesting Lab Environment

VPLE is an intentionally vulnerable Linux virtual machine. This VM can be used to conduct security training, test security tools, and practice common penetration testing Labs. In VPLE bunch of labs Available.

> #### The default login and password is `administrator`:`password`.


## Features

- 7+ Vulnerable Web Application 
- Automation
- Easy To Use
- Beginner Friendly
- Running On Virtual Machine so not effect on Host-Machine (Real-computer)
- Not installing any extra software like Web-server

#### Power on the VPLE :-
Once the VM is available on your desktop, open the device, and run it with VMWare Player. Alternatively, you can also use VMWare Workstation or VMWare Server.

#### Login in the VPLE :-
The login for VPLE is 

username:- ``administrator``.
password:- ``password``.
#### Identifying IP Address of the VPLE :-
After you login to VPLE, you can identify the IP address that has been assigned to the virtual machine. Just enter ``hostname -I`` at the prompt to see the details for the virtual machine.

## How To Use

### Getting Started
After the virtual machine boots, login to the console with username `administrator` and password `password`. From the shell, run the `hostname -I` command to identify the IP address.

> Note: Only run in VMWare Pls Don’t run in VirtualBox

#### Vulnerable Web Services

VPLE has deliberately vulnerable web applications pre-installed. The web server starts automatically when VPLE is booted. To access the web applications, open a web browser and enter the URL where `<IP>` is the IP address of VPLE.
In this example, VPLE is running at IP 192.168.255.143. Browsing to `http://192.168.255.143/` shows the web application home page.
To access a particular web application, just type IP address then enter the port no of Particular web application lab. 

#### List Of All Labs :-

- Web-dvwa 
- Mutillidae 
- Webgoat 
- Bwapp 
- Juice-shop 
- Security-ninjas 
- Wordpress 

| Labs | Lab URL |
| ------ | ------ |
| Web-dvwa | eg. 192.168.255.143`:1335/` |
| Mutillidae | eg. 192.168.255.143`:1336/` |
| Webgoat | eg. 192.168.255.143`:1337/WebGoat/` |
| Bwapp | eg. 192.168.255.143`:8080/install.php` & 192.168.255.143`:8080/install.php` |
| Juice-shop | eg. 192.168.255.143`:3000/` |
| Security-ninjas | eg. 192.168.255.143`:8899/` |
| Wordpress | eg. 192.168.255.143`:8800/` |
### Contact:- DarkKing6@protonmail.com 
## License

DarkKing

**Free Software, Hell Yeah!**

