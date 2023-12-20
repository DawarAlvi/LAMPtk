# LAMPtk
<img src="https://img.shields.io/badge/Python-ffff00?style=for-the-badge&logo=python&logoColor=black" /> <img src="https://img.shields.io/badge/TKinter-3776AB?style=for-the-badge" />

Apache Server and MySQL GUI Frontend written in Python and Tkinter. The aim of this Utility is to provide a lightweight and easy way to manage your Apache and MySQL services during development.

![image](https://github.com/DawarAlvi/LAMPtk/assets/46403138/9024a20f-6d1c-4240-95f7-26d4257e4ed8)

## Installation
LAMPtk uses tkinter library. Make sure its installed.
```
$ pip install tkinter
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
