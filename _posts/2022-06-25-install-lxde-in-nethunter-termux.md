---
title: Install lxde in kali nethunter (Termux NO ROOT!)
Subtitle: Lxde in Kali Nethunter (Termux)
cover-img: https://frix.pythonanywhere.com/admin/fileadmin/download/images.jpeg
thumbnail-img: https://frix.pythonanywhere.com/admin/fileadmin/download/images.jpeg
tags : [howto,Termux, Android Tricks]

---

## What is LXDE ?
LXDE (abbreviation for **L**ightweight **X**11 **D**esktop **E**nvironment) is a free desktop environment with comparatively low resource requirements. This makes it especially suitable for use on older or resource-constrained personal computers such as netbooks or system on a chip computers.

## Installation Requirements

So now i am assuming you have Nethunter in termux and you did all necessary and compulsory steps from installation guide after installation. Don't know how to install Kali nethunter ? ([click here](https://asahluma-tyika.github.io/2022-06-24-install-kali-on-android/))
- Minimum Storage of 1.5GB
- Internet connection (Fast one😄)
- Kali nethunter Installed ([click here](https://asahluma-tyika.github.io/2022-06-25-install-kali-on-android-no-root/))

## Installation 

if you've met the above requirements then you can proceed with the installation

1) Update and upgrade your terminal
~~~
$ apt update && apt upgrade
~~~

2) Install Lxde 
~~~
$ apt-get install lxde-core lxde kali-defaults kali-root-login desktop-base
~~~

3) Grab a cup of hot coffee ☺️ or just tea (sucks 🤧) , It will take couple of days😳, 😁 just kidding it will take minutes to install depending on your internet connection


4) Now Lxde is installed ☺️, But how does it start?, Follow below steps.

- Download and Install **Xserver XSDL** App From Play Store or [Click here](https://play.google.com/store/apps/details?id=x.org.server)
- Now open your installed app and download additional fonts ( 60 Mb) 
- Wait for 3-4 seconds 
- Now minimize the XSDL app and goto termux 
- Now execute this command in Nethunter 
~~~
$ DISPLAY=127.0.0.1:0 PULSE_SERVER=tcp:127.0.0.1:4712 startlxde &
~~~
- Go back to Xserver XSDL App and wait up to 5 seconds then you will get LXDE desktop environment

And start Hacking 👨🏽‍💻 😂 Ethically of course 🌚


## Previews (Screenshots)

![Crepe](https://4.bp.blogspot.com/-pvECOgc8c84/W0B7PWUdlzI/AAAAAAAADMQ/GmUy8vyK_jgaXcR1jnO5BQHl0KA4HRIDQCLcBGAs/s1600/Intex%2BAqua%2BTrend_2018-07-07-09-27-58.png){: .mx-auto.d-block :}

![Crepe](https://4.bp.blogspot.com/-X2tomc4O3bI/W0B7SStOgzI/AAAAAAAADMU/brP-QImT99MO51hd0ToyGJzJ9pziF_PzACLcBGAs/s1600/Intex%2BAqua%2BTrend_2018-07-07-09-27-39.png){: .mx-auto.d-block :}

![Crepe](https://2.bp.blogspot.com/-jPkrKb0IyaA/W0B7XRwjx1I/AAAAAAAADMY/dG5O32Zyti0JRfnrjwoD7YBPhJxg1Gr4wCLcBGAs/s1600/Intex%2BAqua%2BTrend_2018-07-07-09-22-39.png){: .mx-auto.d-block :}
