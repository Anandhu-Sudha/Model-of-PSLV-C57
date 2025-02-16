# Model-of-PSLV-C57
Made an exhibition model of PSLV-C57

#throwback-jan-2024

![image alt](https://github.com/Anandhu-Sudha/Model-of-PSLV-C57/blob/4263ca6ff5ea75b8582c4c8313d36fe8207e022a/pictures/full%20size.pn)

This was for a school exhibition, the body of the model is made with PVC pipes and Polystyrene. It has some light show and sound effect ( countdown announcement and propulsion sound effect).

This was also implemented with Arduino (Nano). A microcontroller is not required for creating a simple led chaser circuit, but considering the time and effort needed to build a chaser circuit from ground, spending money for the Arduino was the wise choice. 

![image alt](https://github.com/Anandhu-Sudha/Model-of-PSLV-C57/blob/4263ca6ff5ea75b8582c4c8313d36fe8207e022a/pictures/circuitry.jpg)

one more nano was inside the enclosure 😉


Also there was a mp3 module attached to play the countdown and sound effect. Here I've used a 'DF Player mini mp3 Module' which was cheap and easy to interface with the Nano. An amplifier module and speaker was also used.

Df player mini mp3 module 👇

![image alt](https://github.com/Anandhu-Sudha/Model-of-PSLV-C57/blob/4263ca6ff5ea75b8582c4c8313d36fe8207e022a/pictures/IMG20240120124912.jpg)


The build was pretty straight forward apart form the one issue that I've Noticed.

It was the day i realised Arduinos can't be used for multitasking. I wanted to blink all red LEDs on the top at once and to sequentially rotate the LEDs at the bottom, at this point I realised this two separate codes can be programmed at once. Other option is adjust the timing and insert codes according to the delay.. but that also failed. Finally I had to use another Arduino nano to do these two separate patterns.

Some ws2812b LEDs strips were lying around, so added that too.

Some pictures and videos are added .

Full working video 👇

https://github.com/user-attachments/assets/803852a5-1b8f-4726-9896-f6e50dad8644


