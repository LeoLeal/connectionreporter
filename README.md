Connection Reporter
=========================================
An Appcelerator Titanium Module

This is an Appcelerator Titanium Mobile Module for reporting Internet Connection Types, since Appcelerator Titanium's ti.network only reports if the device is online or offline.

This module was created cause I needed to get the type of the connection the device was getting when a network change event is fired, so I could treat requests in a more specific way.

HOW TO USE
-------------------------
If you want to simply use this module, just download the dist/modules folder and copy It's contents under the Titanium SDK modules folder in you computer.

The module will be selectable in you Titanium project with compatibility for both iOS and Android Platforms.
The module exposes a method .getConnectionType() that returns a String with the name of the Network Type.

Possible names are None, Unknown, Unknown Network, Unknown Mobile, GPRS, EDGE, CDMA, UMTS, 2G, EVDO, HSPA, HSDPA, HSUPA, HSPA+, 3G, LTE, 4G and Wifi

You can use this method at any time in runtime to consult the network state, but It's recommnded to put It on a Ti.Network change event.
