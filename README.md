# 6B2 Network

This repository acts as a log and documentation for the isolated network at the back of 6B2 for both current and future users of it.

To update this document so that future year groups and teachers can understand how the network works, please fork the project, make the changes and then create a pull request.

## About

The network was built from old computer that the school no longer need. It aimed to allow students to learn about networks, programming, security, etc. in a safe environment that can be easily rebuilt and restored and one that is isolated from the main school network. It consists of a server and 4 clients. They were originally loaded with Windows and Windows Server Edition, although they became disused when the involved teachers and students left the school. Due to insufficient documentation, they have since been wiped and replaced with Ubuntu and Ubuntu Server. This is one of the main reasons for creating this document, since the attached piece of paper was not sufficient. This document also helps students to learn about GitHub and the Git workflow.

## Current state

### Ubuntu

The computers are currently installed with Ubuntu 18.04. Linux was chosen over Windows due to its bash terminal, ease of scripting and to allow students to understand how to use Linux.

These are some resourses about Ubuntu and how to use it:
- https://www.makeuseof.com/tag/ubuntu-an-absolute-beginners-guide/
- https://www.dedoimedo.com/computers/ultimate-linux-guide-for-windows-users.html
- https://www.tutorialspoint.com/ubuntu/ubuntu_software_center.htm
- http://linuxcommand.org/index.php
- https://tutorials.ubuntu.com/tutorial/command-line-for-beginners#0
- https://askubuntu.com

### Server

This has currently been installed with Ubuntu Server and has been partially setup. The username is `server` and the password is `root`. For internet access, a Wi-Fi dongle is required to connect to a tethered 3G/4G hotspot. 

### Clients

The computers are currently connected to the server, but do not utilise it much and they are mostly used as standalone computers. They are named `6B2-1` to `6B2-4`. The root account usersname is `root` and the password is `root`. The standard account username is `student` and the password is `student`. 

`6B2-4` is currently the only fully setup computer, although all are completely functional. All of the major scripting languages have been installed and XAMPP has been installed to use as an Apache server. Apache and MySQL was attempted to be installed manually, but this caused too many issues and was abbandonned in favour of XAMPP, so there may be some issues regarding port clashes. There is a script on the desktop to open XAMPP, which should be opened with the option to `Run in Terminal`, as a terminal window must be open whilst XAMPP runs. There is also a shortcut to the `htdocs` folder to put the website files in. 

`6B2-3` has been partially setup with XAMPP and scripting langugage installations, althought it is not fully finished. `6B2-1` and `6B2-2` have not had any setup after installing Ubuntu and setting up the accounts. To install any other languages, open Terminal and run the command `sudo apt-get [NAME OF LANGUAGE]`. To install XAMPP, follow this tutorial: https://www.wikihow.com/Install-XAMPP-on-Linux.
