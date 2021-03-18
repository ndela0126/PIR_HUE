# PIR_HUE
PIR_HUE is ment to controll Philips Hue lights with a NodeMcu 1.0(ESP 12-E Module). With a timer function in the code that will shut the light off if no active motion is detected.If motion is detected before the timer is up the timer will reset. This is good for high traffic areas such as kitchens and living rooms allowing the light to stay on and not keep turning on and off as the case with the built in timer in the pir sensor.

# Building the Arduino 
PIR sensor VCC pin requires 5V and the problem is the NodeMcu only supplys 3.3V fortunatly there is a work around that requires a little bit of simple soldering  


Instructions for the developer setup for hue can be found at https://developers.meethue.com/develop/get-started-2/
