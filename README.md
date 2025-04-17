This is a variation of SirGoodenough https://github.com/aderusha/MQTTCarPresence/blob/master/readme.md.  
I did not build the esp switch.  I actually used NexxGarage hardware.  When they started becoming 
unrealiable and left backdoor open for people to hack.  I built my own smart garage door opener.  
I used one esp32 to control 2 doors.  I then was able to use the NXG-200 as the switch in the car.  
I figured out how to flash them with Tasmota.  I then simply pluged them into the cars power ports.  
They work very good for this because of having external antenna.  I then added some features to the 
MQTTCarPresence.  One of being it will retry until door is closed.  I also included an override feature.  
I use this when working in garage and don't want doors to open or shut while working in garage when 
working on vehicle, or stop wife from accidently openning door when getting things down off ceiling.  
I also added feature to shoose how long before door shuts.  
