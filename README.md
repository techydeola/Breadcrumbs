# Breadcrumbs Dependencies Setup

1. **Install Tor**
   
   ```sudo apt-get install tor```
   ##
2. **Install Stem**
   
   ```pip install stem```
   ##
3. **Install Socks Supprot library**
   
   ```pip install requests[socks]```
   ##
4. **Append the code below to the `/etc/tor/torrc` file**
   
   ```ControlPort 9051```
   
   ```CookieAuthentication 1```
   ##
6. **Start the Tor Server**
   
   ```sudo service tor start```
   ##
7. **Verify that the tor server is running**
   
   ```sudo service tor status```
   ##

