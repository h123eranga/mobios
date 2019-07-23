# mobios
This is a mobile operating system whch can run only web applications.

Concept
.......
Planning to have linux kernel to deal with hardware. Creating the os as a web browser application boots up and there is a communication layer to communicate with linux kernel from the browser app. Simply the os will be a browser. Each application run on a new tab in browser. The landing browser tab would be the home screen in mobile.

How it works?
.............
App developers will add there web app configurations on mobios apps store. User will install the configuration and browser will pick that and add the widget icon and name in the landing browser tab. So, once the user clicked on app icon browser will open a new tab for the web app. Developer is responsible to get user interaction because the app just display as a web app. 
The middle layer mentioned in the concept will deal with linux kernel and browser requests. 

Example of accessing camera
...........................
If any of the app is trying to access device camera. First, javascript request is passing through browser to middle layer and then pass it directly to the linux kernel.


All rights reserved by mobios.
