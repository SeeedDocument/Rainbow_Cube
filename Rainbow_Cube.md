#Lipo Rider Pro
----
##Introduction

![](https://raw.githubusercontent.com/SeeedDocument/Lipo_Rider_Pro/master/images/LiPo_Rider_Pro.jpg)

In this box, you’ll find everything you need to build a ready to shine Rainbow Cube! 
Have some fun and start creating a masterpiece today with this 4x4x4 RGB LED cube kit from Seeed Studio:
The “Rainbow Cube – Ready to Shine” requires no soldering and comes pre-assembled with a Rainbowduino (Arduino-compatible) LED driver controller. Just plug it in to your PC or Mac, grab a copy of the free design software, and you’ll discover just how easy it is to program this spectacular device and see the results in real time.

The Pack consist of:

- 1 x Rainbow Cube Kit ( Assembled )
- 1 x Rainbowduino v3.0
- 1 x Power adaptor
- 1 x USB cable

Seeed Studio has made a video to show how to use Rainbow Cube and program to it. Watch the video, you'll know how cool this product is.

- Curing program makes Rainbow Cube Kit PnP
- Diaphanous Acrylic sheet makes the shining LEDs looks so cool
- Programmable property let the Rainbow Cube shining in your style

Here is the link in YouTobe: http://youtu.be/v44i73zmwA4

**Great thanks to Riley Porter @Synthetos, for the excellent job of Acrylic Case design.**

[![](https://raw.githubusercontent.com/SeeedDocument/Seeed-WiKi/master/docs/images/get_one_now.png)](http://www.seeedstudio.com/item_detail.html?p_id=992)

##Features

- Maximum 1A load output
- Battery and Solar panel connector is JST 2.0
- Stable 5V USB power supply regardless of source
- Charge/Recharge algorithms built into chip
- Charge Lithium Polymer Battery through solar power or USB
- Stable supply voltage through either lithium battery or USB
- 2 x USB ports let you program your kit while charging your Lithium battery
- LED indications for battery full or charging states
- Scalable to multiple lithium batteries and large/multiple solar panels through simple end-user modifications
- 4 green LED instruct quantity of electricity of lithium battery

##Application Ideas

- Green Power and backup supply for distributed outdoor sensor network
- Charger for Lithium batteries
- Charger for mobile phone

## Cautions

- The LiPo Rider Pro has different connectors from LiPo Rider v1.0, the former is JST 2.0 and latter is JST 2.54.
- Live exposed electronic components
- The board may get hot when supplying large loads
- Potential short circuit or electric shock, especially if device gets wet when placed outdoors for solar power collection

##Dimensions

The dimensions of LiPo Rider Pro is like the [6A Lithium Polymer Battery](https://www.seeedstudio.com/item_detail.html?p_id=602)

![](https://raw.githubusercontent.com/SeeedDocument/Lipo_Rider_Pro/master/images/Liporiderprod.jpg)

###Specification
|Items                    |Min      |Norm       |Max      |
|-------------------------|---------|-----------|---------|
|V`in` Solar              |4.8V     |5.0V       |6.5V(10s)|
|I`charge` (R`Iset`=3.9kΩ)|400mA	|500mA	    |600mA    |
|I`load`                  |0mA		|           |1000mA   |
|V`batt`(Rx=0Ω)           |4.2V                           |
|V`source`USB	          |5.0V                           |
|V`destination`USB	      |5.0V                           |

###Pin definition and Rating
####Pin Instruction and LED Statement

|CH pin level(Red LED state)|OK pin level(Green LED state)|Statements|
|---------------------------|-----------------------------|----------|
|low level(on)	            |high level(off)	          |Charging  |
|high level(off)	        |low level(last on)	          |Complete  |
|pulse signal(flash)	    |pulse signal(on)	          |The battery isn't exist|
|high level(off)	        |high level(off)	          |Two situations :
-      Input voltage lower than gate voltage
-      The input voltage lower than battery voltage|

####LED Battery Indicator

The LiPo Rider Pro has four LED battery indicators like the cell phone,and you can see the battery power by just pressing the button K2.

LED battery indicator parameter:

|Numbers of lighting up     |Quantity of electricity      |
|---------------------------|-----------------------------|
|4	                        |90~100%                      |
|3	                        |60~90%                       |
|2	                        |30~60%                       |
|1	                        |10~30%                       |
|0	                        |0~10%                        |

##Usage
###Example
####Outdoor Sensor Device Power Supply
One important application of the Lipo Rider Pro board is as an affordable power supply for outdoor sensors. The outdoor sensor device will be powered by the lithium battery supplemented by the solar panel. Please note that it is not recommended to run the outdoor sensor ONLY on solar power, as this may vary during the day and may cause the sensor to reset / power down unexpectedly. In this case, the device is running in “USB Mode”.

If a firmware reprogram for the outdoor sensor device is required, simple connect the mini USB port to your PC which will put the device under “Program Mode” as explained above.

Larger/multiple batteries and/or solar panels can be used, but only with end-user modifications.
![](https://raw.githubusercontent.com/SeeedDocument/Lipo_Rider_Pro/master/images/Lipo-Rider-pro.JPG)
####Charge Lithium Polymer Battery through solar power
![](https://raw.githubusercontent.com/SeeedDocument/Lipo_Rider_Pro/master/images/LiPo_Rider_Pro1.jpg)

##Resources

* **【PDF】**[Schmatics](https://github.com/SeeedDocument/CAN_BUS_Shield/raw/master/resource/CAN-BUS_Shield_v1.2.pdf)
* **【Datasheet】**[DSE-CN3065](https://github.com/SeeedDocument/Lipo_Rider_Pro/blob/master/resource/DSE-CN3065.pdf) 
* **【Eagle】**[Eagle File](https://github.com/SeeedDocument/Lipo_Rider_Pro/blob/master/resource/Lipo_Rider_Pro_v0.9b.rar)

##Is this page helpful
<iframe style="height: 600px; width: 500px; margin: 10px 0 10px;" allowTransparency="true" src="https://www.surveymonkey.com/r/TGBWXK7" frameborder="0"></iframe>
