KiCad PMOD compatible connector Library
=======================================

KiCad Library to make it easy to create both host boards and expansion boards
and which are compatible with the [Digilent
"PMOD" specification](http://www.digilentinc.com/Pmods/licensing.cfm).


Library has;
 * Schematic components for "Host Side" and "Device Side" for the following PMOD types;
  * Type 1 - GPIO (plus what I call Type 1A which is a "dual" Type 1 connector).
  * Type 2 - SPI
  * Type 2A - Expanded SPI
  * Type 3 - Old style UART
  * Type 4 - New style UART
  * Type 4A - Expanded new style UART
  * (TODO) Type 5 - H-Bridge
  * (TODO) Type 6 - Dual H-Bridge

 * (TODO) PCB module footprints.
 * (TODO) KiCad templates

Contributing
======================

I **love** contributions. Just fork and send me a pull request! 

**If I don't respond to your pull request within a couple of days, please poke
me!**

If you make (or convert) these to Eagle, I'd be more than happy to include a
link to your repository.


Author & License
======================

This library was created by [Tim 'mithro' Ansell](https://blog.mithis.net/).

This library is released under the 
[Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).

If you use this library for anything, I'd love an [email](mithro@mithis.com)
with a picture of the project (of course this isn't *required* at all). People
making open source hardware make me happy!
