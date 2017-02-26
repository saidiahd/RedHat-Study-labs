# Red Hat Cert Labs (Lab Environment for Red Hat certifications)

## About
TODO
## Architecture
TODO
## Requirements
In order to deploy Labs environments, we will need those 2 OSS:
- [Oracle VM VirtualBox](https://www.virtualbox.org): VirtualBox is a general-purpose and cross-platform  full virtualizer for x86 hardware, targeted at server, desktop and embedded use.
- [Vagrant](https://www.vagrantup.com): Vagrant is an open-source software product for building and maintaining portable virtual development environments.

### 1. Install Requirements for Debian-based Linux , Ubuntu/Mint (64-bit):
**1.1 Install virtualbox:**
```shell
$ wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
$ wget -q https://www.virtualbox.org/download/oracle_vbox.asc -O- | sudo apt-key add -

$ sudo sh -c 'echo "deb http://download.virtualbox.org/virtualbox/debian `lsb_release -sc` non-free contrib" > /etc/apt/sources.list.d/virtualbox.org.list'

$ sudo apt-get update
$ sudo apt-get install dkms
$ sudo apt-get install virtualbox-5.1
```
**1.2 Install Vagrant:**
```shell
$ wget https://releases.hashicorp.com/vagrant/1.9.1/vagrant_1.9.1_x86_64.deb
$ sudo dpkg -i vagrant_1.9.1_x86_64.deb
```
### 2. Install Requirements for Debian-based Linux , Ubuntu/Mint (32-bit):
**2.1 Install virtualbox:**
**2.2 Install Vagrant:**
```shell
$ wget https://releases.hashicorp.com/vagrant/1.9.1/vagrant_1.9.1_i686.deb
$ sudo dpkg -i vagrant_1.9.1_i686.deb
```
### 3. Install Requirements for RedHat-based distributions (64-bit):
**3.1 Install virtualbox:**
**3.2 Install Vagrant:**
### 4. Install Requirements for RedHat-based distributions (32-bit):
**4.1 Install virtualbox:**
**4.2 Install Vagrant:**

## Deploy Lab Environment
TODO
## Lab Credentials
TODO
## How to use it ?
TODO
