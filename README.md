# PiratePython - Alpha

A minimal, robust ground-up build of Raspbian for Python programmers.

Ever wanted the operating system to get out of your way and just let you write Python? PiratePython aims to bring the simplicity of
MicroPython to the Pi, but all the power of the full-blown Python you're used to.

Just edit main.py with your project, watch your changes reload as you save them, and see debug output over serial with PuTTY.

It's also rock solid and stateless, meaning it's mighty difficult to render unbootable.

For the enterprising hacker, there's SSH access, a wireless Access Point mode, boot.py and boot.sh scripts for customisation and more!

Built using ali1234's fantastic rpi-ramdisk tooling: http://github.com/ali1234/rpi-ramdisk

# This is an alpha!

PiratePython is still in early alpha development stages. This build wont harm your Pi, but is likely to behave in weird, unpredictable ways.

Operating support is patchy at the moment, YMMV but you should have the best experience with Windows 10, OSX or Linux. Earlier versions of Windows will require some drivers/fiddling.

Currently USB Ethernet is not supported at all under OSX, but we're working on it.
