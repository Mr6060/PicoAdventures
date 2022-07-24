# PicoAdventures
This is a library of my Raspberry Pi Pico projects.

### 1602lcd
This library controls a standard 1602 lcd screen. This does not use I2C, it uses an 8bit shift register for the data pins, meaning the effective amount of pins used on the pico board is slightly reduced (not as much as i'd like with an I2C interface, but I don't have that and couldn't be bothered, I used what I had)

It is not yet finished, it has 2 basic functions to execute a command and writing a character.

More to come
