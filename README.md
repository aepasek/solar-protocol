# Solar Protocol

A system for load balancing and serving content based on photovoltaic logic.
=======
A repository in development for a solar powered network of servers that host a distributed web platform. Project by Tega Brain, Alex Nathanson and Benedetta Piantella. Supported by Eyebeam Rapid Response for a Better Digital Future fellowship.

## Installation

https://github.com/alexnathanson/solar-protocol/blob/master/installation.md

## API documentation

https://github.com/alexnathanson/solar-protocol/blob/master/API.md

## Hardware Troubleshooting & Maintenance

https://github.com/alexnathanson/solar-protocol/blob/master/troubleshooting-and-maintenance.md

## TO DO
* make an installer.sh
* X move python templater to server 
* check any limits on the DNS api
* find a better way to update IP addresses to add or remove a server
* do we want to include a blacklist to control enrollments?
* make sure the point of contact log starts rewriting data after 100 entries and doesn't keep adding data forever
* decide on best security.  eg. could generate an api key and it adds it to each device. 
* make a script for pull updates from the git repo that automates resetting permissions as needed

## FRONT END
* Code for an energy responsive front end is in test-site folder
* To test, set up a virtual environment and install requirements.txt

## FRONT END TO DO
* X Set up with real solar data from index.php
* Basic energy data collection for different sized pages and traffic. 
* Energy impact of regenerating page. What's the frequency of this?
* X move python script to backend
* add server name to device log file and fix index.html to display name.

