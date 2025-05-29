# KAVACH
A PROJECT CREATED BY TECH MASTERS

Problem Statement:

########################




Solution and approach:

#############################





Features:

1. Personal Security: Provide an effective tool for women to enhance their safety in public and private spaces.


2. Real-Time Alerts: Send alerts to pre-configured emergency contacts when a distress signal is triggered.


3. Location Tracking: Provide GPS & GSM-based real-time location tracking for swift assistance.


4. Emergency Communication: Enable voice-activated or button-triggered emergency protocols.

5. Live Footage Capture: Embedded Camera for live footage recording.
      
6. Provides a means of Defense to the user: Wearable spark generator.



Tech Stack:

Voice activated spy Pendent system, Activates camera and sound recording, the ESP 32 camera records and stores the video in jpg format in a memory chip which can be collected and used for evidence.

GPS, GSM system activated using the same voice command, both GPS and GSM are connected to the same microcontroller, the Node MCU microprocessor chip(ESP8266) gets the location info by 3 satellite locking GPS module and transmits it through the GSM module using their respective data lines.

The GPS module generates the location info in the form of latitude and longitude which is processed by the GSM module and is sent through the communication lines to the receivers device in the form of an SMS message with Google map link. The real time location of the user is constantly sent through the SMS every 30 seconds as encoded in the processor which can be changed as well. 

For Extended protection a wearable high voltage teaser is added which provides the user a means of defending themselves if necessary, every component is designed to activate wirelessly with a single voice command.


Run Instructions:

A pre encoded activate command is present which can be used to activate the entire system, and it can be changed using voice prompts. The camera starts recording, the GPS module starts locking the satellites to gain location and the GSM module sends that location info through the SMS services to receiver's device. 

