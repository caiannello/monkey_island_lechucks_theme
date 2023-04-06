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
   *** OPL3 VERSION:  (For an Arduino MEGA2560 
                        and a YMF262-M)

   YMF262 PIN     ATMEGA2560 PIN
   ----------     --------------
   D0...D7        PORTA.0...7
   /irq           PORTD.0  (unused)
   /rd            PORTD.1  (unused)
   /wr            PORTD.2
   a1             PORTD.3  (unused)
   a0             PORTH.0
   /cs            PORTH.1
   /rst           PORTJ.0
   
   Similar version to this one on youtube:
   https://www.youtube.com/watch?v=wUJ-r6xru18
------------------------------------------------
```
