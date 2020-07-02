# S4-Changelog

Changelog for the services and systems we use to run S4 Sustainable Hosting

At S4 we believe in accountability, transparancy and open source software. We also believe in a lot of other things, but those are the most relevant to this document. We have chosen to make this changelog publicly visible so you can see how we are running and constantly developing our hosting platform. 

Our main services are all hosted at the sustainalbe Telia Helsinki Data Centre, with backups and utilities hosted at a sustainable Ineterxion data centre in Amsterdam.

* Our web servers are CentOS and run LiteSpeed Enterprise web server, with Cyberpanel as a control panel. 
* Our mail servers are Ubuntu and are running our customised version of Mail-in-a-box. 
* Our analytics servers are CentOS, running OpenLiteSpeed and Matomo analytics.
* Our utilities server running various monitoring services is Ubuntu and runs Statping as an uptime monitor.

### Changelog 
Major OS, infrastructure, and software component updates listed only.

01/07/20

Removed Google Analytics tracking from S4 sites and switched to our own Matomo analytics. 

29/06/20

Implemented new uptime monitoring and status page system, based on Statping

27/06/20

Moved backup servers from Frankfurt to Amsterdam
(data centre has better PUE rating)

11/06/20

Updated MIAB 0.45 -> 0.46 
(to address Roundcube security vulnerability)

8/06/20

Updated web and analytics servers
CentOS 7 -> CentOS 8

27/05/20

Updated Maria DB on webservers -> 10.4.13

18/05/20

Updated MIAB 0.44 -> 0.45 
(including Roundcube update 1.4.2 -> 1.4.4)
