# IoT-Connector
Full Screen Android App with Side-Launcher to Quickly Switch between IoT devices, Octoprint Ports, Websites and more!
Designed to be used with Android Jelly Bean, or Android 4.1 and up.

1.) Copy the iot_connector directroy to your Android Device Internal Storage Root. 
2.) "iot_connector" directroy you can edit the "IoT_Connector_Manifest.xml" to add as many links as you like.
3.) The images for your links go into the "iot_connector/Images" folder
4.) Menu id="0" must remain, the default path should staty the same Path="/", Icon and Splashscreen need to be in the iot_connector directroy root, Icon and SplashSc reen Images can be changed, but suggest you keep the names of the files.
5.) <Menu Id="0" Name="Default" Path="/" Icon="default-icon.png" SplashScreen="default-splash.png" Background-Color="#000000"/>
6.) Install the "IoT_Connector.apk", you will lkely need to allow untrusted sources as this app is not in the Goolge Play Store. 
7.) After you open the app you will see the menu open on the right with all of the locations you specifed in the "IoT_Connector_Manifest.xml"
8.) When you click the link, the menu will hide and you will see the splash screen just before the site is loaded.
9.) The menu does not require you to swipe from the left side edge of the screen, to make this work all of the way back to Android Jelly Bean so older Android device could be used, you can just swipe right on an area on yor page without any controls.
10. If the menu is open and you wnat to stay on the page, then swipe left.  
11.) to refresh a page, swipe right and select the link for taht page again.


This is just a simple full screen app and was desiged for connecting to ESP32 webserver devices, OctoPrint ports, and other IoT projects.

