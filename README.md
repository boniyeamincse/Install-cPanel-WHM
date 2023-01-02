# Install-cPanel-WHM

When setting up a new CentOS 7 server, you may find yourself looking for control panel software that will allow you to manage your websites and web applications in a graphical user interface. One of the most popular web hosting control panel solutions is cPanel/WHM. This software gives you a comprehensive control panel interface that allows you to manage and customize many different aspects of your server in a user-friendly environment. In this article, we will outline how to prepare your CentOS 7 server and install cPanel/WHM using the command-line interface. Before performing the steps in this guide, please ensure that you have set up root SSH access on your server.

Topics Include:

 1.Preparing for Installation
 2.Installing cPanel/WHM
**Prepare for Installation**
Before you can install cPanel/WHM on CentOS, you will first need to disable your server’s firewall, the Network Manager, and SELinux.  

1. First, stop the service using the following command:
