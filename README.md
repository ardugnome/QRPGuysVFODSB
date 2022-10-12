# QRPGuysVFODSB
A fork of the original QRP Guys FT8_VFO.030521
Purpose is to expand bands offered and  to correct FT8 Frequencies found in the original code.
Secondary purpose is to add CHU and WWV frequencies.

First upload October 2, 2022

Display will now read bn 160 for 160m, bn 6 for 6m, bn 4 for 4m, bn 1.2 for 1.2m, bn .70 for 70cm for ham bands

WWV stations begin with bn 2.5 for 2.5MHz, bn 5 for 5MHz, bn 10 for 10MHz and bn 15 for 15MHz. More information here https://en.wikipedia.org/wiki/WWV_(radio_station)

CHU station will read bn3.33 for 3.33MHz. More information here https://en.wikipedia.org/wiki/CHU_(radio_station)

!!! WARNING !!!  4m band is not available in the USA and many other countries, it was included for our friends across the pond. More information here https://en.wikipedia.org/wiki/4-meter_band

You are responsible for everything that goes wrong, including my bad code! 

1. I assume you have an external programmer, if not buy one, or make it.

2. Prepare your Arduino environment by downloading https://github.com/technoblogy/atmegabreadboard the hardware recognition code and put it in your Arduino's IDE hardware directory. If you don't have it create it.

3. Make sure your settings correspond to the JPEG file shown here.

4. You may have to burn a bootloader if the sketch is slow to respond (Chances are it is running internal oscillator)

5. Don't forget to choose Sketch>Upload Using Programmer when uploading your code.

v1.1 Update 10/11/2022 (changed time stations to display "bt" instead of "bn")

WWV stations now read bt 2.5 for 2.5MHz, bt 5 for 5MHz, bt 10 for 10MHz and bt 15 for 15MHz. CHU station reads bt3.33 for 3.33MHz. 
