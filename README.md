# MacroKeyboardV2
13-Key Arduino ProMicro USB Macro Keyboard
https://youtu.be/IDlcxLQ1SbY?si=J5Tzyvr0lGsu_4_Y

![cache_4109089450](https://github.com/retrobuiltRyan/MacroKeyboardV2/assets/68818321/6268292e-356e-4ce5-aecd-476bc4bc1897)


Trouble Shooting Tips and FAQs
Some basic trouble shooting:

 1. This PCB is not plug-and-play. You have to upload at least the example code linked from this product description. Code is on this page.
 2. Use the Arduino IDE to program. (see arduino.cc for help with adding libraries and getting the software to program the Arduino).
 3. Make sure you have these libraries added:
 4. Make sure the Arduino Micro 32u4 is selected when programming this board. Tools> Board> Arduino Micro.
 ![cache_4108825371](https://github.com/retrobuiltRyan/MacroKeyboardV2/assets/68818321/db1c5b3a-c5bf-4db2-9a99-5da5c854a6f8)

Go to Tools>Manage Libraries.


![cache_4108825370](https://github.com/retrobuiltRyan/MacroKeyboardV2/assets/68818321/09200526-0732-40ad-bdef-3d5f52008c62)

2) Make sure you have the Arduino Pro Micro selected. Tools> Board> Arduino Micro

5. Make sure all the solder jumpers are soldered! You’ll get really weird results (phantom keys) if you miss a jumper.

6. You may have to hold down the reset button, hit upload sketch, wait for the IDE to try to ‘upload’ to the Arduino, then release the reset button.
The boot-loader for uploading is a short window in the Arduino Pro Micro. The Pro Micro wants to default to the USB HID mode. Catching the short window for uploading a program might take a few tries; i.e to get a feel for the timing (my experience).
Search for these libraries. When you find the library listed below, install it.
7. DO NOT SOLDER BOTH I2C power jumpers. Solder only one!
8. ![cache_4109097346](https://github.com/retrobuiltRyan/MacroKeyboardV2/assets/68818321/747f8cd8-cfca-4bee-a014-230513090e00)
