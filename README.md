# Neptune-E-Coder or Pro Read Water meter reader
Separate programs (1. e-coder 2. ProRead)
 Arduino Water Meter Reader and Ethernet Server.
Every hour the Arduino queries the E-Coder or Pro read water meter for usage and writes the result to an SD card.
On query the Ethernet Server sends data.
The request for data can be; 
1. last 24 hours, 
2. All data last 7 days, 
3. All data last 31 days, 
4. Once a day all data.
5. All data

The Sensus SRII water meter is read by a ESP8266 controller. The controller is connected to a standard PC.
The power is supplied by a USB connector. The Output is read by an arduino IDE.
