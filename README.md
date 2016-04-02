# arduino-scrambling-example
Example of Modified Arduino Optiboot Firmware to handle sort of encryption

## Disclamer
This repository is dedicated to a specific mission on freelancer.com
If you are not the person who created a project on Freelancer.com named 'Copy-protected Arduino-like bootloader and .hex scrambler' then you should pass away, there won't be anything intersting for you

## For Freelancer Employer
### Message for you
I want to work with you. I have the required skills. Instead of talking much, i prefer provide you a demonstration of my abilities.

I have made a working modification of Arduino's bootloader to only accept Hex files encrypted with a specific key.

I have also made a python script which will 'encrypt' a standard Hexfile so that it can be correctly interpreted by the modified bootloader.

This repository is here to provide a POC (Proof Of Concept) of my working programs (both Bootloader and Python script).

The bootloader i have used is not the same you provided for some simple reason :
- It was not working on my arduino Uno rev 3 (since quite a long time, the prefered bootloader is Optiboot, it is not much different than the one you provided on Freelancer.com. If you want me to make the modification on it, it won't be a problem, the code is almost the same. It was just easier to do it on Optiboot for testing purposes).
- It is more recent, i supposed that i would maybe like to use the oportunity of this project to upgrade your current Firmware/bootloader (as said above, if you need me to change your bootloader, it will be done in a few minutes since both codes are almost the same).

### How to Use 
I hope you have an Atmega328P with you, if you don't please contact me, i will find a solution.
You first need to upload the modified bootloader Hex file. I won't give details since you looks comfortable with Makefiles and C code. If you need help, again, just contact me, you can also use Github Issues to communicate with me if needed (i don't know Freelancer much, i am new here, i don't know if you have to pay to communicate with freelancers or if it's free).
After uploading the modified bootloader, just upload my example-heartbeat.hex file using the traditionnal arduino upload way.

### What it is supposed to do
You should see on LED13 (the orange LED on the Arduino Board) blink a bit like a Heartbeat (it is just a modified version of the famous Arduino Blink Example)
To confirm that the Hex file is Encrypted, you might revert back your arduino to the original bootloader and see that the example-heartbeat.hex file won't work after upload

### Conclusion
I hope you will make it works and understand that i really want to work with you.
I am ready to implement any improvement you might suggest :
- increase strongness of the encryption, since the example provided can be quite easily cracked (the key is only one byte, but i will increase its size if you want)
- ...
And naturally, i am ready to deliver all to you as soon as you select me as your employer (no delay to wait, code is ready)

I hope you will like the way i tried to catch your attention (and that you will read this whole long speech ... sorry for that)

### Again, if it doesn't work for you (don't have an Atmega328p), just ask i can make other bootloaders !

Have a nice day, and hope to work with you soon !


