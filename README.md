# Welcome to abcdesktop.io

abcdesktop.io is a native cloud desktop, and a complete work environment accessible from a simple HTML 5 web browser, without any installation.
This flexible working environment simplify usage like :

- Telecommuting
- Remote virtual desktop 
- IT temporary acess for subcontractors
- Training  

## abcdesktop.io: a docker VDI service

abcdesktop.io provides a way to run grapicals applications securely isolated in a docker container, and use a web browser HTML5 as display device. Because dockers containers are lightweight and run without the extra load of an operating system, you can run many graphical applications on a single kernel or on a kubernetes cluster.

![screenshot-applications](img/screenshot-applications.png)


## Quick installation for kubernetes
You can watch the youtube video sample. This video describes the Quick installation process.

<iframe width="640" height="480" src="https://www.youtube.com/embed/KpjG4ksoGNI" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>

Download and extract the latest release automatically (Linux or macOS) or read the step by step installation process [abcdesktop for kubernetes](/setup/kubernetes_abcdesktop.md)

```
curl -sL https://raw.githubusercontent.com/abcdesktopio/conf/main/kubernetes/install.sh | sh -
```

## Quick installation for docker (personal use, Non-cluster mode)
You can watch the youtube video sample. This video describes the Quick installation process.

<iframe width="640" height="480" src="https://www.youtube.com/embed/_A80Sy9g28I" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>

Download and extract the latest release automatically (Linux or macOS) or read the step by step installation process [abcdesktop for docker](/setup/dockermode.md)

```
curl -L https://raw.githubusercontent.com/abcdesktopio/conf/main/docker/install.sh | sh -
```

## Features

- Access to the user home directory (homeDirectory support in Active Directory)
- All applications run inside an isolated docker container
- Support Microsoft Windows applications using Wine
- GNU/Linux X11 applications native support
- No need to install applications any more
- Local and remote printing support 
- Off-line sessions are maintained


### Supported Web browser HTML 5

abcdesktop.io uses many modern web technologies. However these are the minimum versions we are currently aware of:

* Chrome 49, 
* Firefox 58, 
* Safari 11, 
* Opera 36,  
* Microsoft Edge (based on Chromium)
