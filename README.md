# HTTP Presence
SmartThings mobile presence detection is limited to what the iOS, Android or Windows app currently reports.  If the user disables their location services, or the app crashes, the presence detection is incorrect.

This simple app tries to incrementally improve the presence detection by letting you poll a LAN web service for additional information.  For example, your router may publish a list of active MAC addresses, or another smart device might return additional presence information. 

This app requires you to also update your mobile presence sensor to add a present() command.  <a href='https://github.com/KristopherKubicki/smartapp-http-presence/blob/master/smartapp-mobile-presence.groovy'>I have provided one</a> in this repo as well. 

License
-------
Copyright (c) 2015, Kristopher Kubicki
All rights reserved.
