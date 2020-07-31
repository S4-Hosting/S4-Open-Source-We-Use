# S4 - Open Source Philosophy

---

A list of the open source services and systems we use to run S4 Sustainable Hosting.

At S4 we believe in accountability, transparancy and open source software. We also believe in a lot of other things, but those are the most relevant to this document. We have chosen to make this list publicly visible so you can see how we are running and constantly developing our hosting platform. Some people might argue that this is a bad idea for 'security through obscurity' reasons, but we disagree.  

Our main services are all hosted at the sustainalbe Telia Helsinki Data Centre, with backups and utilities hosted at a sustainable Ineterxion data centre in Amsterdam.

* Our web servers are CentOS and run Open Litespeed or LiteSpeed Enterprise web server, with Cyberpanel as a control panel. 
* Our mail servers are Ubuntu and are running our customised version of Mail-in-a-box. 
* Our analytics servers are CentOS, running OpenLiteSpeed and Matomo analytics.
* Our utilities server running various monitoring services is Ubuntu and runs Statping as an uptime monitor.

---

### Projects we actively use...

#### Matomo - https://github.com/matomo-org/matomo
For all of the obvious data privacy and ownership reasons we don't use Google Analytics or similar, but instead install ethical analytics on our own sustainably hosted servers. There are a few options, Matomo is the best we've found so far. 

#### Statping - https://github.com/statping/statping
We want to love Statping so much, it's the uptime monitor and status page generator that we are using at the moment, but it's not quite where we would like it to be

#### Mail in a Box - https://github.com/mail-in-a-box/mailinabox
Running and maintaining a mail server with high deliverabilty is hard and time consuming, but at least you can make sure that setting one up is quick, easy and done right. We love MIAB and it's what we use as a base for all of mail servers. 

#### Open LiteSpeed - https://github.com/litespeedtech/openlitespeed

#### Cyberpanel - https://github.com/usmannasir/cyberpanel

---

### ...and ones we are watching

#### Open Web Analytics - https://github.com/Open-Web-Analytics/Open-Web-Analytics

#### Cachet - https://github.com/CachetHQ/Cachet

#### Boxbilling - https://github.com/boxbilling/boxbilling
