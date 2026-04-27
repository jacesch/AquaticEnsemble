README
======

Project Name: Aquatic Ensemble
Authors: Hanna Christensen & Jacey Schell
Date: 04/28/2026


WHAT THIS IS
------------
Aquatic Ensemble is a multi-user, interactive electronic ensemble that relies on real animal recordings to generate instruments within the ensemble. User interactivity through Makey-Makey controllers and x-IMU3s alters the visual and musical composition of the simulation. Through this installation, we seek to translate complex biological concepts into an accessible, interactive audiovisual experience. We allow our users to perceive underwater sounds and processes that humans don’t typically interact with in their lifetime. 



HOW TO USE IT
-------------
1. Ensure installation of Ableton Live 12 Suite, TouchDesigner, and x-IMU3 GUI applications
2. Download entire repository
3. Connect router to iMac via ethernet
4. Turn off iMac Wifi and connect to router in network settings
5. Open x-IMU3 GUI application
6. Connect x-IMU3 (3) to iMac via USB 
7. Select and open x-IMU3s in GUI
8. Ensure these settings:
	- Wireless -> Wi-Fi -> Client Mode
		- SSID: Router Username
		- Key: Router Password
		- Channel: 36 (5 GHz)
	- Wireless -> Wi-Fi -> UDP
		- IP Address: Router IP Address
		- Send Port: 8003
		- Receive Port: 9000
9. Unplug x-IMU3 USB connections and reconnect to GUI via UDP
10. Close x-IMU3 GUI and turn off x-IMU3s
11. Open Ableton Live project and TouchDesigner project
12. Select x-IMU3 track with max patch in Ableton session
13. Turn on first x-IMU3 and press "connect" under the "1" circle in the max patch
14. Repeat for other two x-IMU3s
15. Connect Makey-Makey Controllers via USB to iMac
16. (Optional) Alligator clip PlayDoh to Makey-Makey "Click," "Space," and ground
17. Connect display to second iMac via AirPlay and drag TouchDesigner performance window to second display
18. Select Ableton window and watch as audio and visuals react in real time!




WHAT YOU NEED TO KNOW
---------------------
Requirements:
- Ableton Live 12 (v.12.2.5)
- Max (v.9.0.7)
- TouchDesigner (v.2025.31760)
- Ableton LiveGrabber library
- TP-Link TL-MR3020, 5 GHz, via ethernet (or other personal wi-fi router)
- iMac, M3, 16GB RAM (2)
- MicroUSB (3), Ethernet (1), Alligator Clips (7)

Important settings:
- Ensure iMac is on network and NOT wi-fi
- x-IMU3 GUI Send Port: 8003
- x-IMU3 GUI Receive Port: 9000

Troubleshooting:
- x-IMU3s aren't connecting in Ableton → Close out of GUI and Max Applications
- CSV Data File not found → Change path in TouchDesigner
- If AirPlay doesn't work → Connect external computer (on same wi-fi of second iMac) via HDMI to router-connected iMac




NOTES
----------------
Future Ideas:
- More animals/species!
- Better casing for x-IMU3s 
- Polished controllers
