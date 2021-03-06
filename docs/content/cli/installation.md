---
title: Installation
weight: 20
---
menu:
  main:
    parent: cli

# Installation

Vamp requires Java version 8 to be installed. 

To verify if the correct Java version has been installed, type 
{{% copyable %}}
```
java -version
``` 
{{% /copyable %}}

It should report back the version as 1.8
```bash
java version "1.8.0_45"
Java(TM) SE Runtime Environment (build 1.8.0_45-b14)
Java HotSpot(TM) 64-Bit Server VM (build 25.45-b02, mixed mode)
```

For further installation steps, please check the section appropriate for your platform:

* [Debian](#debian)
* [Red Hat](#redhat)
* [OSX](#osx)
* [Windows](#windows)

## <a name="debian"></a>Debian / Ubuntu
A detailed explanation on how to install Java 8 on Debian / Ubuntu can be found here: 
http://www.webupd8.org/2014/03/how-to-install-oracle-java-8-in-debian.html

To add the Vamp Debian repository & install the vamp-cli package:
{{% copyable %}}
```bash
echo "deb https://dl.bintray.com/magnetic-io/debian wheezy main" | sudo tee -a /etc/apt/sources.list
sudo apt-get update
sudo apt-get install vamp-cli
```
{{% /copyable %}}

Now you can run the Vamp CLI, by typing 
{{% copyable %}}
```
vamp
```
{{% /copyable %}}


## <a name="redhat"></a>RedHat / CentOS

TBD

## <a name="osx"></a>OSX

TBD

## <a name="windows"></a>Windows

TBD