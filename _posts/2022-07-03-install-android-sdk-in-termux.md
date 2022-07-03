---
layout: post
title: Install android SDK in Termux
comments: true
subtitle: Android Software Development Kit in Termux
---

## What is android SDK?
The Android SDK is a software development kit that includes a comprehensive set of development tools. These include a debugger, libraries, a handset emulator based on QEMU, documentation, sample code, and tutorials. 

## Installation requirements
- Java [apt install openjdk-17]
- High speed internet connection

## Installation
1) Update and Upgrade your terminal
~~~
$ apt update && apt upgrade
~~~
2) Download Android SDK zip file
~~~
$ wget https://github.com/Lzhiyong/termux-ndk/releases/download/android-sdk/android-sdk-aarch64.zip
~~~
3) Unzip / Extract into **share** directory
~~~
$ unzip android-sdk-aarch64.zip -d $PREFIX/share
~~~
4) Make a wrapper file for sdkmanager
