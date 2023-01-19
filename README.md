# Install-cPanel-WHM

When setting up a new CentOS 7 server, you may find yourself looking for control panel software that will allow you to manage your websites and web applications in a graphical user interface. One of the most popular web hosting control panel solutions is cPanel/WHM. This software gives you a comprehensive control panel interface that allows you to manage and customize many different aspects of your server in a user-friendly environment. In this article, we will outline how to prepare your CentOS 7 server and install cPanel/WHM using the command-line interface. Before performing the steps in this guide, please ensure that you have set up root SSH access on your server.

Topics Include:

 1.Preparing for Installation
 2.Installing cPanel/WHM


<h1>**Prepare for Installation**<h1>
Before you can install cPanel/WHM on CentOS, you will first need to disable your server’s firewall, the Network Manager, and SELinux.  

1. First, stop the service using the following command:


# SIEM Training

## General
- Jose Bravo - What is a SIEM? (5 Vídeos): https://www.youtube.com/watch?v=MtqFMe4zSpQ&list=PLHh9jhztlMyp8lyKXt9orVM57ygW_ihPS
- IPPSec - PowerSIEM Analyzing Sysmon Events with PowerShell: https://www.youtube.com/watch?v=MvfhIydxFmw

## AlienVault OSSIM
- Cybrary - AlienVault OSSIM: https://www.cybrary.it/course/alienvault-ossim/

## Elastic
- Elastic - SIEM Fundamentals: https://www.elastic.co/training/elastic-security-fundamentals-siem

## ArcSight (2 séries/paylists de vídeos)
- Paul Brettle - What is Series: https://youtube.com/playlist?list=PL_JhopV-r9zLigctFEOzic-af0sEuHZ-x
- Paul Brettle - ArcSight ESM 101: https://youtube.com/playlist?list=PL_JhopV-r9zIXDz0pX2dmSJvBGVkczF5y

## QRadar
- Jose Bravo - QRadar (38 Vídeos): https://www.youtube.com/watch?v=P90e4iEJ32s&

## Splunk
- Splunk - What is Splunk?: https://education.splunk.com/course/what-is-splunk
- Splunk - Intro to Splunk: https://education.splunk.com/course/intro-to-splunk-elearning
- Splunk - Using Fields: https://education.splunk.com/course/using-fields
- Splunk - Scheduling Reports & Alerts: https://education.splunk.com/course/scheduling-reports-alerts-elearning
- Splunk - Visualizations: https://education.splunk.com/course/visualizations-elearning
- Splunk - Search Under the Hood: https://education.splunk.com/course/search-under-the-hood-elearning
- Splunk - Intro to Knowledge Objects: https://education.splunk.com/course/intro-to-knowledge-objects-elearning
- Splunk - Intro to Dashboards: https://education.splunk.com/course/intro-to-dashboards-eLearning
