---

published: true
layout: post
title: Case Study: Toward Point of Care Data Collection in the Bateyes
author: Chris MacKay
comments: true

---

## Background

Gathering data about the patients seen during batey clinics has been identified as a major hurdle in terms of allow us to understand what the mobile medical clinics are accomplishing.

To this end, I though I would try to implement a 

## Set Up

### Materials and Cost:

- Raspberry Pi, USB-powered mini-computer to function as a web and database server - US$40
- TP-Link Mobile WiFi Router, a usb-powered router to create the local WiFi network, US$30
- Anker 1200mAh battery pack, a rechargeable power source $50
- **Total:** $110

### Technology:

- OS: Raspian Wheezy
- Server: Apache2
- database: mySQL
- webapp framework: flask

### Powering On and Setting Up

Note: you can instead simply put the disk image I created (complete with the OS, dependencies, the web application, and some demo data) onto your own SD card.

1. create an OS image on an SD card and install rasperian
2. access your pi via ssh and update and upgrade software
3. configure the pi
	1.      $ sudo raspi-config
	1. the memory usage to be 100% CPU
	1. allow full use of disk
1. Install Apache
2. Install Flask
3. Install FTP
4. Install the app

### The App

I wrote a web app in python (via flask) that would allow for what I hoped would be rapid and easy data entry via a touchscreen (tablet or phone) into a web form. This form would submit the data to a database on the backend, which would allow fairly easy analysis later on.

The data points I wanted to collect were:

- Demographics:
	- age
	- gender
	- location of residence
- Vital Signs:
	- weight
	- blood pressure
	- heart rate
- Disease Information:
	- 

## The database 

## Workflow

### Turning everything on upon arrival:

To startup the server, router, unit, all you have to do is…

### Entering Data

We chose to try to collect just a few basic demographic and disease data points from the patient we had seen. The easiest way to do this was at the pharmacy. I set up my iPad and had one person at the pharmacy designated to enter the information once each card  



## Results

## Conclusions