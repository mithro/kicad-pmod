KiCad PMOD compatible connector Library
=======================================

KiCad Library to make it easy to create both host boards and expansion boards
and which are compatible with the Digilent "PMOD" specification.

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


PMOD
======================

Pmod interface or Peripheral Module interface is a standard defined by Digilent
Inc in the
[Digilent Pmod™ Interface Specification](http://www.digilentinc.com/Pmods/licensing.cfm)
for peripherals used with FPGAs or micro-controllers.

A lot of [Pmod information is collected in the following Google Spreadsheet
](https://docs.google.com/spreadsheets/d/1D-GboyrP57VVpejQzEm0P1WEORo1LAIt92hk1bZGEoo/edit#gid=826995092)

The PMOD header is found on a wide variety of FPGA boards including many not
developed by Digilent,

 * [Atlys](http://www.digilentinc.com/atlys/)
   a Xilinx Spartan 6, video testing platform.
   The board only has 1 "dual" PMOD header by default but can have another 4
   dual added by the vmod-mib expansion board.

 * [Zybo](http://www.digilentinc.com/Products/Detail.cfm?NavPath=2,400,1198&Prod=ZYBO),
   A low cost Xilinx Zynq development board.
   The board has 5 dual PMOD headers and one dual Analog PMOD header.

 * [Zedboard](http://zedboard.org/product/zedboard),
   A higher end, very popular Xilinx Zynq development board.
   The board has 5 dual PMOD headers.

 * [Mimas V2](http://numato.com/us/fpga-boards/xilinx/spartan6.html)
   A budget Spartan 6 board with plenty of power.
   The board has 5 dual PMOD headers.

 * [Arty A7](https://reference.digilentinc.com/reference/programmable-logic/arty-a7/start)
   An affordable Xilinx Artix-7 development board.
   The board has 4 dual PMOD headers.

Example Pmod expansion boards can be purchased from;

 * Digilent at http://www.digilentinc.com/Products/Catalog.cfm?NavPath=2,401&Cat=9
 * Numato at http://numato.com/fpga-boards/expansion-modules.html
 * Zedboard at http://zedboard.org/accessories/pmod
 * Maxim at http://www.maximintegrated.com/en/design/design-technology/fpga-design-resources/pmod-compatible-plug-in-peripheral-modules.html

PMOD "Extensions"
---------------------

There are a number of unofficial extensions to the PMOD standard. These include;
 * Using multiple PMOD headers which are next to each other.
 * An "Analog PMOD header" found on the Zybo.
 * An "High speed PMOD header" found on the Zybo.


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
