# Door Lock Security System

The project is about securing door lock in office/home which is automated through bulk SMS service, RFID tag reading and  live camera streaming.

### Applications of Door Lock Security System
	+	The door lock security system can be used in any building to safeguard and check who is entering or trying to enter in the building.
	+	It can be used in personal home, hospitals, institutions, offices etc.

### Hardware components required:
	+ Raspberry Pi 3 B+
	+ RFID module MFRC522
	+ RFID tag
	+ 12V electronic door lock
	+ Door lock driver
	+ Power Adapter / Battery
	+ Internet
	+ Bulk SMS service
	+ Breadboard
	+ Connecting wires


### Circuit diagram explanation:
Analog output (A0): Real-time output voltage signal on the thermal resistance.
	+ RFID module MFRC-522: The module is used to identify any tag placed on it.
	+ RFID tag: The tag stores information, and the information is stored in the access-log. If the information matches with the information stored in the access-list then the lock is opened.
	+ 12V door lock: The lock is opened when a 12V passes through it.
	+ Door lock driver: The door lock driver makes the door lock compatible with raspberry pi
	+ Bulk SMS service: The SMS service is used to send SMS to the admin number to inform about any intrusion
	+ Camera: A camera is kept for live streaming

### Code for Door Lock Security System:
The code is added in the python script in the repository

### Important Aspects of the Program:

When we developed the project ,the one important aspect we kept in mind is the real world scenario. An invasion can occur any time (24/7). This means our system must constantly monitor fire 24/7 all the month and year. In the program, we loop with while 1, and escape the loop if keyboard interrupt occurs function has the necessary conditions to check fire.

