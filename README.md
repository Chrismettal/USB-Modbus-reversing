# USB-Modbus reversing <!-- omit in toc -->

[![License: CC BY-SA 4.0](https://img.shields.io/badge/license-CC%20BY--SA%204.0-blue?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Shop: Tindie](https://img.shields.io/badge/shop-Tindie-blue?style=flat-square)](https://www.tindie.com/stores/binary-6/?ref=offsite_badges&utm_source=sellers_Chrismettal&utm_medium=badges&utm_campaign=badge_medium)
[![Donations: Coffee](https://img.shields.io/badge/donations-Coffee-brown?style=flat-square)](https://github.com/Chrismettal#donations)

Documentation of a reversed no-name USB to Modbus converter. It seems to be using some non-standard automatic DE/NRE handling that I would like to use for my [PiPLC project](https://github.com/chrismettal/piplc) for software that can't use manual DE/NRE switching, light Home Assistant.

A KiCAD project is included, but only for reversing the original PCB, and not to recreate a new one. Though I might change my mind later.

**If you like my work please consider [supporting me](https://github.com/Chrismettal#donations)!**

## Table of contents <!-- omit in toc -->

- [Original](#original)
- [Reversing](#reversing)
- [Donations](#donations)
- [License](#license)

## Original

TODO

## Reversing

TODO

## BOM 

Temporary BOM before KiCAD project is created

R1 "752" 7k5
R2 "224" 220k
R3 "222" 2k2
R4 "472" 4k7
R5 "222" 2k2
R6 "203" 20k
R7 DNP

C1 DNP
C2 DNP
C3 112nF
C4 6.7uF
C5 113nF
C6 40pF

U1 CH340G ?
U2 MAX485 ESA +2314

Q1 "HM6C"

D1 6V8A
D2 6V8A
D3 6V8A

Crystal "12M" DNP

## Donations

**If you like my work please consider [supporting me](https://github.com/Chrismettal#donations)!**

## License

 <a rel="CClicense" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
