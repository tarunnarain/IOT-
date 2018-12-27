# IOT-
Reading LDR sensor data and uploading it inBOLT cloud and ploting result in Thinkspeak in Real time  
IoT-with-Data-Analytics
The intensity data of an LDR connected to Bolt IoT platform is retrived in real time over the internet using ThingSpeak service which then analyzes and plots the data as required

In this project, we are collecting the live data from an LDR(Light Dependent Resistor) which is connected to an IoT platform named “BOLT IoT”. The collected data is then passed to an IoT data analytics website called “ThingSpeak” which retrieves, analyzes and visualizes the data. This is done using Matlab which is in-built into the website as a feature.

The process is explained in the following steps:-

Step 1: Setting Up BOLT

*First step is to connect the BOLT to a Wi-Fi network. •	The BOLT creates its own hotspot when you power it on for the first time. •	Remove the SD card from the BOLT and access the file which has the details to connect to the hotspot. •	If we want to connect the BOLT to our own Wi-Fi instead, we have to enter the details in the same file.
•	Save the file and insert the SD card back into the BOLT and power it up. •	Now BOLT will connect to the Wi-Fi network. •	If BOLT is properly connected then the blue light will stop blinking and it becomes stable. •	We need to write a code to sense the data from the LDR and pass it to the Thingspeak website. •	Now we have to find the IP address of the BOLT. Advanced IP Scanner can be used to do that. •	Now type IP address/developer in a browser and upload the code in the upload box. •	Now type the IP address and hit enter.

Step 2: Getting Started With ThingSpeak

•	Open https://thingspeak.com and create a new account. •	Open your account and click on new channel. •	A channel stores the data that we send to thingspeak. •	A channel can have 8 fields for storing data of any type. We need only one to store the LDR data. •	Now click on API key and copy the key.

Step 3: Finishing the things up

•	Now enter the read API key of the channel and enter it in the HTML page coded earlier. •	Click on read API button and then pass it Thingspeak button. •	After taking and passing a couple of readings, our data can be visualized over various MATLAB plots.
