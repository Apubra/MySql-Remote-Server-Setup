# MySql-Remote-Server-Setup

Install and use xampp on linux ubuntu 22.04; Through this tutorial, we will learn how to install and use xampp on linux ubuntu 22.04 system using terminal or command line.

How to install XAMPP on Ubuntu 22.04 using Terminal
Follow the following steps to install and use xampp on linux ubuntu using terminal or command line:

Step 1 – Update System Packages
Step 2 – Download XAMPP On Ubuntu
Step 3 – Install XAMPP On Ubuntu
Step 4 – Open Web Dashboard and phpMyAdmin using Xampp

Step 1 – Update System Packages
First of all, open terminal or command and execute the following command on command line to update system packages:

sudo apt update
sudo apt upgrade -y
Step 2 – Download XAMPP On Ubuntu
Below is the command to download the complete for each Php version. Whatever version of Php you have installed. According to it, you can use it by selecting the recording command of your requirement from the command given below:

With PHP 8.1


wget https://www.apachefriends.org/xampp-files/8.1.1/xampp-linux-x64-8.1.1-2-installer.run
With PHP 8.0:

wget https://www.apachefriends.org/xampp-files/8.0.14/xampp-linux-x64-8.0.14-1-installer.run
With PHP 7.4:

wget https://www.apachefriends.org/xampp-files/7.4.27/xampp-linux-x64-7.4.27-1-installer.run
With PHP 7.3:


wget https://www.apachefriends.org/xampp-files/7.3.33/xampp-linux-x64-7.3.33-0-installer.run
With PHP 7.2:

wget https://www.apachefriends.org/xampp-files/7.2.34/xampp-linux-x64-7.2.34-0-installer.run
Step 3 – Install XAMPP On Ubuntu
Once the xampp has been downloaded, Then execute the following command on the command line to install xampp on ubuntu:

chmod a+x xampp-linux-*-installer.run
After that, run the installer script.

### PHP 8.1 example ###
sudo ./xampp-linux-x64-8.1.1-2-installer.run

### PHP 7.4 example ###
sudo ./xampp-linux-x64-7.4.27-1-installer.run

