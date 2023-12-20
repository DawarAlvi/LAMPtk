# LAMPtk
<img src="https://img.shields.io/badge/Python-ffff00?style=for-the-badge&logo=python&logoColor=black" /> <img src="https://img.shields.io/badge/TKinter-3776AB?style=for-the-badge" />

Apache Server and MySQL GUI Frontend written in Python and Tkinter. The aim of this Utility is to provide a lightweight and easy way to manage your Apache and MySQL services during development.

![image](https://github.com/DawarAlvi/LAMPtk/assets/46403138/9024a20f-6d1c-4240-95f7-26d4257e4ed8)

## Installation
LAMPtk uses [tkinter](https://docs.python.org/3/library/tkinter.html) library. Make sure its installed.
```
$ pip install tkinter
```
Clone the repo and move the lamptk.py script to a location that's in the $PATH global variable (assuming ~/.bin)
```
$ git clone https://github.com/DawarAlvi/LAMPtk.git
$ cp LAMPtk/src/lamptk.py ~/.bin
```

## Usage
LAMPtk make call to [systemd](https://systemd.io/) to manage the Apache and MySQL services. It is recommended to run LAMPtk with root priveleges. 

```
$ sudo ./lamptk.py
```

Alternatively you can run it from the terminal without root privileges, however systemd will prompt you to enter the password every time.

```
$ ./lamptk.py
```
