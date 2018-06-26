# Bare Bones Arduino
The only way to save huge amounts of (battery) power when running an Arduino

# See video #117 at https://www/youtube.com/ralphbacon  
(Direct link to video: https://youtu.be/F0Ew68AbI_Q)

So in videos #115 and #116 we've discovered that the Arduino Uno/Nano ATmega328P chip can be run using just microamps of power and awoken with either a trigger or a timer respectively - but only when constructed in a bespoke manner.

It's easy to do, and I show you here the handful of components you need to construct the absolute minimum Arduino configuration, how to upload a Bootloader to your naked ATmega328P chip, and finally how to upload code to the new chip.

So now we can make the chip sleep for 99% of the time, and just wake up now and again to do its business (just like a baby)!  

All the links to products I mentioned (with which I have no connection whatsoever)  

The 3.3v / 5v FTDI USB to Serial converter. Get one. In fact, get a couple as they are extremely useful in other situations too.  
https://www.banggood.com/FT232RL-FTDI-USB-To-TTL-Serial-Converter-Adapter-Module-For-Arduino-p-917226.html  
At the time of writing, Banggood were selling these for less than £2 each, with free shipping. All the Far Eastern warehouses (AliExpress, GearBest, Amazon and your favourite auction site eBay will stock these. **Make sure it is the dual voltage type**)  

28-pin ZIF (zero insertion force) socket for the ATmega328P chip  
https://www.aliexpress.com/item/2-PCS-LOT-16-20-28-40-Pin-2-54MM-Green-DIP-Universal-ZIF-IC-Socket/32655076081.html  
At the time of writing, you could get two of these for £1.43 with free shipping (I've just ordered these!)  

The ZIF booloader shield we stumbled across towards the end of the video, makes it very easy to load the bootloader using an Arduino  
https://www.aliexpress.com/item/AVR-ISP-Shield-Burning-Bootloader-Programmer-Atmega328P-Bootloader-module-with-buzzer-and-LED-indicator-for-Arduino/32853007180.html  
At the time of writing, this was just 2.89 - I've ordered one.

If you like this video please give it a thumbs up, share it and if you're not already subscribed please consider doing so :)

My channel and blog are here:  
------------------------------------------------------------------  
https://www.youtube.com/RalphBacon  
https://ralphbacon.blog  
------------------------------------------------------------------  
