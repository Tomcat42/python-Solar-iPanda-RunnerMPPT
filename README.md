# python-Solar-iPanda-RunnerMPPT#

A python module to communicate with the iPanda MPPT Runner Solar Chargers.

What is the "iPanda Runner MPPT" ?
The iPanda MPPT Runner is a series of Solar Chargers for different Battery
types and Voltages from an chinese Vendor.
  - Vendor home page: http://www.wipanda.com/en/index.php
  - known Models:
      Explorer-M
      Runner
      Explorer
      eSmart3
      Master
      Mars 
      Galaxy

The Charger has electrical connections for
- solar pannels (as solar power source)
- Battery (to charge and to get Power from)
- DC Load (to connect power consumer, switchable)
- Temperature sensor (analog, electrical)
- one electrical RS-485 interface
  with 2 Sockets, Type 8p8c (commonly known as RJ45)
  this can be used to connect more than one device to the RS-485 bus.
  In this case, the controller have to be configured to different addresses.

A Java based Application running even under wine is called
 "MyGreen Solar Monitor",
 ... which has a default password "mpptsolar" to access the first time...
 Look here: https://www.youtube.com/watch?v=p0fIsuIQN4o

The RS-485 works at the setting 9600 Baud, 8N1.

The Protocol description can be found in chinese Language in the Web.

