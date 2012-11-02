Organization: mySociety, UK (http://www.mysociety.org/)

Goal: Develop a common phone application for the FixMyTransport (http://www.fixmytransport.com/) service of mySociety.

Application Name: FixMyTransport Mobile 

Project Synopsis: FixMyTransport is a web-based service provided to the citizens of UK by mySociety, a charitable organization. It helps people report problems while they are travelling by public transport such as train, bus, tram or ferry. The problems are reported to the customer service department of the operator of that particular transport through the FixMyTransport application. These are also displayed on the FixMyTransport web site. This approach is proven to be very effective in solving some of these problems. My attempt here is to mobile enable this existing application to report such problems. This will improve this service in three ways:
1) People can report problems while they are in transit, using the phone on hand.
2) They can use the GPS service of the phone to capture their location automatically.
3) They can use the camera in the smartphone to take a photo of the problem and attach it to the report as well. 

Architecture and Design: 
Instead of building the user interface in the native GUI (such as Java for Android) I am using the jQuery Mobile touch-optimized web framework. This is renedered by the browser and so is compatible with a wide variety of smartphones.

For this same reason, I am planning to use the open source Apache Cordova framework for accessing the device features such as the camera, GPS… and so on. 

All of this will eventually allow people with Android, iPhone or other smartphones to access this application. However, at this point I am only focusing on developing and testing for Android.

I was also planning to use the open source OpenLayers JavaScript library for displaying map data in web browsers. However, after making a lot of effort, I found that the OpenLayers support for mobile devices is either not fully ready or not adequately documented. As a result of this limitation, I had to fall back on using the Google Maps API.

Mockups: I have created the mockups (the .ep files) using the open source Evolus Pencil (http://pencil.evolus.vn/) tool. I added the mobile stencils from here (http://code.google.com/p/android-ui-utils/).