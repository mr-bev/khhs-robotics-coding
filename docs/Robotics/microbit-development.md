# Micro:bit Development

## MakeCode
The easiest solution to get started is using [MakeCode](https://makecode.microbit.org/){target="_blank"}. Once you have signed in you can run the simulator to test your code before uploading it to your micro:bit. You can also download a copy of the 

To connect a micro:bit to MakeCode, you can use a USB cable to transfer code or data: 

1. Connect the micro:bit to your computer's USB port using a micro-USB cable. 
1. Open MakeCode for micro:bit in your browser. 
1. Click the purple Download button in the lower left of the MakeCode screen. 
1. Select Pair. 
1. A browser pop-up will let you select your micro:bit and then click Connect. 
1. Select Download and the code will transfer to your micro:bit

### Sharing Projects
How to share projects is details [here](https://makecode.microbit.org/share){target="_blank"}.

### Pros:
- Easy to get started
- Good supporting projects and lots of online documents.
- Convert between block, python and javascript with the click of a button
- Built in simulator to test your code

### Cons:
- Single developer only. No pair programming unless you want to share your projects.

## MicroPython
MicroPython also has an IDE for the [web](https://python.microbit.org/){target="_blank"}. 

### Pros
- MicroPython is support on ESP32 chips and Raspberry Pi giving you more choices for hardware
- Good [documentation](https://microbit-micropython.readthedocs.io/en/v2-docs/){target="_blank"}
- Online IDE is easy to use
- MicroPython is more similar to Python

### Cons
- This will flash the micro:bit to run effectively a different operating system. (It can be changed back)
- Different version of Python to MakeCode
- Some addons may not be supported or require open source solutions
- No official extensions for VSCode

## Visual Studio Code (VSCode)
There a 2 main solutions to use a micro:bit with VSCode. 

1. Use MicroPython (recommended)
1. Use MakeCode cli (not recommended)

### MicroPython
 There is no official extension for VSCode but several users have created their own. I have tried [micro:bit Statped](https://marketplace.visualstudio.com/items?itemName=Statped.microbit) which has worked for me. The instructions for getting it setup are in the link.

### MakeCode 
There are a sequence of instructions that require node.js to be install and the majority of the effort requires you to use the cli (command line interpreter) with pxt files.
    - [https://makecode.microbit.org/code](https://makecode.microbit.org/code)
    - [https://makecode.com/cli](https://makecode.com/cli)





!!! Warning
    This is not recommended

