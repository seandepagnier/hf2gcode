hf2gcode, a hershey font to g-code tracer
=========================================

The work to this has begun in 17. May 2013, so there isn't anything useful here yet.

I think rowmans.jhf would be a nice, simple and fast font for the needler project.

Design
------

There will be a libhf2gcode-dev, a static linkable version which does the actual type setting
and tracing and a CLI programm to call it. Furthermore the libhf2gcode-dev should be compilable
with avr-gcc and run on an AVR Atmega32.

Brainstorming
-------------

http://www.gnu.org/software/libc/manual/html_node/Parsing-Program-Arguments.html

Dependencies
------------

Unsorted Links
--------------

http://en.wikipedia.org/wiki/Hershey_font
http://www.ghostscript.com/doc/current/Hershey.htm
http://emergent.unpythonic.net/software/hershey (Download of the fonts and description)
http://www.timeguy.com/cradek/truetype (A TrueType tracer with DXF and G-Code output)
http://wiki.linuxcnc.org/cgi-bin/wiki.pl?Simple_LinuxCNC_G-Code_Generators#Text_Engraving_Software
http://www.evilmadscientist.com/2011/hershey-text-an-inkscape-extension-for-engraving-fonts/ (Inkscape extension)
