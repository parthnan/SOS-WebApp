# SOS-WebApp
[![HitCount](http://hits.dwyl.com/parthnan/SOS-WebApp.svg)](http://hits.dwyl.com/parthnan/SOS-WebApp)

A web service that is a prototype of a SOS system where users can send SOS messages to a central server alongwith their location. Built using firebase for online DB, JS(Ajax) for communication endpoints, HTML-CSS for design and Google Maps API. Details in the presentation file 'SOSWebApp.pptx'.

Below is a screenshot of the screen on the client side(left~ **send.html**) and server-side(right- Taskforces Side~ **recive.html**). The clientsends a SOS signal with the requisite message, which is reflected in the screen on the right as soon as received.

![alt text](https://raw.githubusercontent.com/parthnan/SOS-WebApp/master/SOSdemo.png)

When the server side clicks on the link for more details, they are led to a page which links to the client sender's location at that time.

![alt text](https://raw.githubusercontent.com/parthnan/SOS-WebApp/master/SOSmap.png)

This simple SOS system has the architecture os a simple client server model via a DB as below.

![alt text](https://raw.githubusercontent.com/parthnan/SOS-WebApp/master/SOSsystem.png)
