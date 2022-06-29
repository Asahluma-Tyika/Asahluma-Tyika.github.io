---
layout: post
title: Flutter in Termux NO ROOT
thumbnail-img: https://frix.pythonanywhere.com/admin/fileadmin/download/20220629_140048.png
cover-img: https://frix.pythonanywhere.com/admin/fileadmin/download/20220629_140048.png
subtitle: install flutter sdk in termux
tags: [Termux,howto,Android Tricks]
comments: true
---

## What is flutter?
Flutter is an open-source UI software development kit created by Google. It is used to develop cross platform applications for Android, iOS, Linux, macOS, Windows, Google Fuchsia, and the web from a single codebase. 

# Installation Requirements
- Android SDK ([Learn how to install](#))
- arm64/aarch64 device

# Installation
If you've met the above requirements then continue with the Installation, follow below steps.

1) apt update and upgrade your terminal (as always).
~~~
$ apt update && apt upgrade
~~~
2) Download and execute(Run) the installer shell script
~~~
$ curl -s https://raw.githubusercontent.com/Hax4us/flutter_in_termux/master/install.sh | bash -s
~~~
3) Then boom you've installed flutter in termux, follow below steps to create and build your project app.
- Login to debian
~~~
$ proot-distro login flutter
~~~
- To create project execute:
~~~
$ flutter create <your-project-name>
~~~
- To build your application execute:
~~~
$ flutter build apk --release --target-platform android-arm64
~~~

#
Now you can learn  and build flutter applications without the need of a laptop or computer just your android phone 👨🏽‍💻☺️

