---
layout: post
title: Install kali on android NO ROOT!
subtitle: Install kali in Termux (NO ROOT)
thumbnail-img: https://frix.pythonanywhere.com/admin/fileadmin/download/image_one_1-min.png
cover-img: https://frix.pythonanywhere.com/admin/fileadmin/download/image_one_1-min.png
tags: [howto,Termux,AndroidHacks]
---

## What is **kali** linux

Kali linux is the most used penetration testing operating system which runs on the Linux kernel. And kali Linux provides up to date 600+ penetration testing inbuilt tools with stable updates and these tools are easy to use and are open source too. So if you would like to use kali Linux not only on laptops and computers but on android mobiles also. Then this tutorial is for you

## Installation Requirements

For correct installation of kali liux on android please have the following requirements

- Termux App (F-DROID)
- 3GB free data storage
- 3/2GB ram for fast and better performance
- No Root Device
- Android 7 and higher

1) If you have the above requirements then go and open Termux and Type the following to upgrade and update the terminal
~~~

$ apt update && apt upgrade

~~~

2) After updating and upgrading termux install basic packages
~~~
$ apt install -y python php curl wget git nano
~~~

3) Now open the home directory and allow termux to access storage
~~~
$ cd $HOME && termux-setup-storage
~~~

4) Download the file to install Kali Linux nethunter
~~~
$ wget -o install-nethunter-termux https://offs.ec/2MceZWr
~~~

5) Open home directory and give permission to the installation file
~~~
$ cd $HOME && chmod +x install-nethunter-termux
~~~

6) Execute the file to start the installation
~~~
$ ./install-nethunter-termux
~~~

7) The installation process can take a lot of time, now grab a coffe and wait for it to complete 100% process. After that exit from termux and then open termux again and follow the below steps. Open termux and type the below command to start nethunter. while accessing the root privilege you may get a request for a password so the password is Kali
~~~
$ nethunter -r
~~~

8) Now, you successfully have installed nethunter os in your termux without any issues, In case if you face any issues please visit this [tutorial](https://www.noob-hackers.com/2021/07/how-to-install-kali-linux-on-android.html?m=1)

9) Now, if you want to use nethunter as GUI (Colourful User Interface) then, follow below steps.
- Install VNC viewer from Google play Store ([click here](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android))
- Open termux and start nethunter as followed in step 6
- After that paste below commands and start using the GUI of nethunter
- In this step you have to give password which is used to access gui of nethunter so,
- While completing steps if you want to access view only password so type (n) there.

~~~
$ nethunter kex passwd
~~~

10) Now, follow this step and after that you can view GUI in vnc viewer app
~~~
$ nethunter kex &
~~~

11) Now, open VNC viewer app and click on plus icon in the app which is located in the bottom. After that click on. A new pop window will be opened in that you can see (new connection) like text, in that below section you can see two options 1) Adress 2) Name
in address section type 127.0.0.1:5901 And in Name type Kali. And click on connect after that it will start your nethunter os and you can use it easyli. And to stop using it disconnect from vnc viewer app and open termux where you started nethunter in that window type below command.
~~~
$ nethunter kex stop
~~~

NOW NETHUNTER WORKS ON VNC VIEWER 😯 COOL RIGHT😂 #Happy Hacking
