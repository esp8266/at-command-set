at-command-set
==============

ESP8266 AT+ Command Set

Few of the commands Listed below have an Inquiry Mode and Test Mode. 
Inquiry Mode will be executed with a ? at the end of the command "AT+CWMODE?" this will return the current status of the Module i.e. CWMODE=3
Test Mode commands will be exicuted with an =? at the end of a command "AT+CWMODE=?" this will return the possible parameters input i.e. 1=Sta, 2=AP, 3=both 

The commands entered has a <CR> at end so do not forget to add a <CR> or else there will be no output.
If you are using firmware version >0.92 you will need carriage return and line feed.


To play around with the AT commands you can connect the ESP8266 to a 3.3v USB-TTL serial cable or Arduino. You can then communicate with the module using tools
such as screen, picocom or the serial monitor in the Arduino IDE. If you can't seem to get a response from the module, try changing your baud rate; different
versions of the board use different baud rates (9600 and 115200 are most common).


Will add rest Soon !
