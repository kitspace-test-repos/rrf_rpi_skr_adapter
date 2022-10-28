Raspberry Pi to SKR/SKR Pro Adapter for ReprapFirmware
======================================================

The adapter sold by TeamGloomy on Tindie for this purpose is sold out.  This
is my equivalent replacement.

Description
-----------

I'm looking at putting ReprapFirmware on my Hypercube 300.  The necessary
adapter to connect its Raspberry Pi Zero 2 W to its SKR Pro 1.2 is
out-of-stock on Tindie.  This is a smaller adapter that does the same thing,
only it plugs into the EXP2 header on the printer motherboard and a 6-wire
cable connects the other end to pins 19-24 on the Raspberry Pi GPIO header. 
(I already have a 4-wire UART connection between the two that also supplies
power; instead of putting in the full 40-pin GPIO header, it only has enough
pins populated for the connections I'm using.)

It was a quick layout to throw together in KiCad; I probably spent more time
playing around with panelization options than on the main layout.  :) I
should have 100 (20x5) bare boards arriving from JLCPCB, and the parts to go
on it are dirt-cheap…should be well under $5 from DigiKey, and probably
under $1 each in quantity from LCSC.

This project is also on
[printables.com](https://www.printables.com/model/262089-raspberry-pi-to-skrskr-pro-adapter-for-reprapfirmw).
