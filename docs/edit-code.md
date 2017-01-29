
## Getting Started

The new site for coding is [http://microbit.org/code/]

They want you to get started quickly and easily, 
so most of the ways you are encouraged to code 
involve online code building tools that run in your browser. 
These sites (also sometimes called REPLs) allow you to 
build up your code and see the results in an emulator, 
before downloading the compiled HEX file to flash to your micro:bit. 

It's incredibly easy so just dive in :) 
Try one of the two simplest scripting tools below. 


### Code Kingdoms - JavaScript

* Nice, easy, editor to get started 
* write simple event-driven code
* switch between block edit view and full text code views
* coding environment allows you to start New projects in other langauges

[https://www.microbit.co.uk/app/]

### Microsoft PXT - JavaScript

* fresh clean interface
* good help system including tutorials 
* lots of block functions available
* switch easily between block editor and code editor
* New Projects always in PXT

[https://pxt.microbit.org/]

## Flashing your code

Flashing code onto the micro:bit is how you get your program on there. 

Again they have made this really simple with the micro:bit, 
and they even have a flashing orange LED on the back 
that lets you know when you are 'flashing' your code. 

They say flashing because in the 1970s some Read Only Memory (ROMs) 
needed to have a strong UV light shined on them to wipe their old contents 
before you could upload a new program onto them. When NAND memory was invented 
in the late 1980s it was called flash memory as it 'flashed' itself without light. Now most permanent storage chips are based on flash memory, but 
search for EPROM if you want to find out more on the history. 


### USB drive

Plug your micro:bit into one of your computer's USB ports 
and it should come up as a storage drive. 
In Linux this should just happen, in Windows 10 you might need to 
be patient (or unplug and replug it) so the driver auto-installs properly. 

### Copy the .HEX to flash

Once you have your micro:bit drive just copy and paste your compiled .HEX file 
into there, and you will see the orange LED on the back flash as the binary is uploaded.


## Ubuntu

### MicroPython

* [http://microbit-micropython.readthedocs.io/en/latest/devguide/installation.html]
* 

This is the fork of MicroPython designed for the BBC micro:bit

The source is [https://github.com/bbcmicrobit/micropython]

### Mu editor

* source [https://github.com/mu-editor/mu]
* 3rd party suggested instructions [http://sakarinkurssit.blogspot.co.uk/2016/11/how-to-get-mu-editor-for-microbit-up.html]
* unofficial linux downloads:
	- [http://blog.gbaman.info/?p=727]
	- 



## OUT

### ARM mbed

BBC got ARM chip designers to help by using their **mbed** platform, 
which supplies useful _stuff_ for small embedded systems like the 
[micro:bit](https://developer.mbed.org/platforms/Microbit/):
* mbed Hardware Development Kit (HDK) to interface with the board
* mbed Software Development Kit (SDK) to develop libraries that work with the board
* mbed compiler to take code and create executables to flash to the board
* mbed online IDE and compiler to support the online coding sites

Have a look at some of the work they put into this board, 
[https://developer.mbed.org/blog/entry/bbc-microbit-mbed-hdk/]
