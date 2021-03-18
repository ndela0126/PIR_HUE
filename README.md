
# PIR_HUE
PIR_HUE is ment to controll Philips Hue lights with a NodeMcu 1.0(ESP 12-E Module). With a timer function in the code that will shut the light off if no active motion is detected.If motion is detected before the timer is up the timer will reset. This is good for high traffic areas such as kitchens and living rooms allowing the light to stay on and not keep turning on and off as the case with the built in timer in the pir sensor.

# Building the Arduino 
PIR sensor VCC pin requires 5V and the problem is the NodeMcu only supplys 3.3V fortunatly there is a work around that requires a little bit of simple soldering like i did with the red wire in the picture below.  
![PIR_VCC_SOLDER](https://user-images.githubusercontent.com/79550376/111706638-0129ab00-8819-11eb-8715-08fe75e3cec2.jpg)

# Philips Hue Developer Setup
Instructions for the developer setup for hue can be found at https://developers.meethue.com/develop/get-started-2/
