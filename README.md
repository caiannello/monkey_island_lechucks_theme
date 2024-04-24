```
   The Secret of Monkey Island - LeChuck's Theme 
   
   Original music from the classic LucasFilm Game
   Composed by Michael Z. Land
--------------------------------------------------
   *** ARDUINO BEEPER VERSION:
   
   Adapted to Arduino from PC speaker version by 
   Craig Iannello (caiannello AT google mail) 
   2020-11-24
  
   To play, hook a piezo speaker between ground
   and pin 8 on your Arduino, and run the .ino 
   file. (Tested on a Nano)
   
   Original song on youtube:
   https://www.youtube.com/watch?v=UGym8xQp7Hc   
--------------------------------------------------
   *** TINY BEEPER VERSION:
   
   Note: The .C file is a separate, standalone
   version, specifically for a little ATtiny85. 
   (It doesn't use the Arduino library.)

   Demo of this version on youtube:
   https://www.youtube.com/watch?v=ET6V49l4CsY
------------------------------------------------
   *** OPL3 VERSION:  (For an Arduino UNO
                           and a YMF262-M)

   YMF262 PIN     ARDUINO UNO PIN
   ----------     --------------
   D0             D2
   D1             D3
   D2             D4
   D3             D5
   D4             D6
   D5             D7
   D6             D8
   D7             D9
   /rst           D10
   /irq           D14
   a0             D15
   a1             D16
   /wr            D17
   /rd            D18
   /cs            D19
   
   Similar version to this one on youtube:
   https://www.youtube.com/watch?v=wUJ-r6xru18
------------------------------------------------
   *** OPL3 HW MODULE:  (YMF262-M)

   Schematics and PCB files
   (Cadsoft EAGLE 4.16r2):

      YMF262-M OPL3 module + DAC + amplifier
      Arduino Nano adaptor board

```
