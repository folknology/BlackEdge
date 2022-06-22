# BlackEdge Nxt

## Blackedge Nxt Interfacing
Connectors are 2 rows of 25 pins each with a 1.27mm pitch, System side is male, FPGA Expansion is female.
![Drwawing](https://github.com/folknology/BlackEdge/blob/master/Drawing.png)
## BlackEdge Carrier Pinouts
![Pinouut](https://github.com/folknology/BlackEdge/blob/master/Schematic.png)

# BlackEdge Examples

## BlackIceMx
Carrier example - [BlackIce Mx](https://github.com/folknology/BlackIceMx)
BlackIceMx - Core Module carrier with MixMods/Pmod interfaces
![BlackIce Mx](https://github.com/folknology/BlackIceMx/blob/master/BlackIceMx.jpg)
![BlackIce Mx](https://github.com/folknology/BlackIceMx/blob/master/cad/BlackIceMx.png)

[Get BlackIce Mx from Tindie](https://www.tindie.com/products/Folknology/blackice-mx/)


![BlackIceMx Schematic](https://github.com/folknology/BlackIceMx/blob/master/cad/BlackIceMx-schematic.png)

Needs to be combined with a Core module, for example [IceCore](https://github.com/folknology/IceCore)

![BlackIce Mx with core](https://github.com/folknology/BlackIceMx/blob/master/BlackIceMx-with-Core.jpg)

Supports MixMods (in addition to Pmods)

![BlackIce Mx fully loaded](https://github.com/folknology/BlackIceMx/blob/master/BlackIceMx-Fully-loaded.JPG)


Supports the [BlackEdge connectivity](https://github.com/folknology/BlackEdge) core modules

More [BlackIce Mx background](https://forum.mystorm.uk/t/new-product-blackice-mx/551/10) on the [forum](https://forum.mystorm.uk/)


## IceCore
Core module example - [IceCore](https://github.com/folknology/IceCore)
IceCore Ice40 HX based modular developement core 

**Top View**
![IceCore Module](https://github.com/folknology/IceCore/blob/master/cad/IceCore.jpg)
**Bottom View**
![IceCore Module](https://github.com/folknology/IceCore/blob/master/cad/IceCore-Bottom.jpg)


**Features**
* Ice40 HX4K - 4K Luts (8K for Yosys), 80/(128)Kbits BRAM, 2 PLLs, NVCM
* 16Mbit SDRAM 16 bits wide (143Mhz)
* 16Mbit Flash QSPI/SPI (100Mhz)
* 56 General purpose IOs, SPI, Uart, I2C/Can
* Stm32F730 200Mhz, 256KB Ram, 64KB Flash
* Triple 2.5MSPS ADCs (interleaved to 7.2MSPS)
* Dedicated Programming and debug USB 2.0FS
* Uart/Application specific USB2.0FS
* Digital video connector
* SDCard connector
* 4 Coloured Status LEDs
* 4 Coloured User LEDs
* 2 User buttons, 1 Mode/Boot buttoni

[Get it from Tindie as part of BlackIce Mx](https://www.tindie.com/products/Folknology/blackice-mx/)

## IceCore Module

![IceCore Module](https://github.com/folknology/IceCore/blob/master/cad/IceCore.png)


![Schematic](https://github.com/folknology/IceCore/blob/master/cad/IceCore-schematic.png)

Core modules can be combined with different carrier boards for example [BlackIce Mx](https://github.com/folknology/BlackIceMx)

Supports the [BlackEdge connectivity](https://github.com/folknology/BlackEdge) carriers

Some further [background information](https://forum.mystorm.uk/t/new-product-blackice-mx/551/10) can be found on the [myStorm forum](https://forum.mystorm.uk)

