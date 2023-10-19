# LoFence V2 Hardware

The LoFence V2 PCB is designed with KiCad.

The BOM has been optimized for being produced and assembled by [JLCPCB](https://jlcpcb.com/). Even the THT components except the big resistors everything should be available there. Disregarding the LA66 module which is not doable in a non-bulk production.

I use the "Fabrication Toolkit" plugin for KiCad aka [JLC-Plugin-for-KiCad](https://github.com/bennymeg/JLC-Plugin-for-KiCad) to one-click export production files.

To complete the PCB you need:

- 2 x 10M resistor rated for 10kV (e.g. Vishay *VR68000001005JAC00* from [tme.eu](https://www.tme.eu/details/vr68000001005jac00/tht-resistors/vishay/))
- 1 x 1M resistor rated for 100V (e.g. Royal Ohm *MGR0W4F1004A10* from [tme.eu](https://www.tme.eu/details/mgr0.25w-1m/tht-resistors/royal-ohm/mgr0w4f1004a10/))
- 1 x [Dragino LA66 module](https://www.dragino.com/products/lora/item/230-la66-lorawan-module.html) for your LoRaWAN frequency band

And to complete a device:

- 1 x [Gainta *G368MF*](https://www.gainta.com/en/g368mf.html) case (e.g. from [tme.eu](https://www.tme.eu/details/g368mf/multipurpose-enclosures/gainta/))
- 4 x 2.9x6.5mm plastic screw (e.g. from [tme.eu](https://www.tme.eu/details/b2.9x6.5_bn14065/screws/bossard/2097273/))
- 1 x double banana socket or any connectors you want to use for positive and negative fence connection (e.g. this from [tme.eu](https://www.tme.eu/details/bc-119/4mm-banana-sockets/sci/)) or similar
- 2 x 40mm wire 1.5mm^2 with M5 cable lugs to connect the PCB with the banana socket (this is what I use)
- 1 x antenna suitable for your LoRaWAN frequency (I get them from Aliexpress)
- \>=50mm antenna cable from IPEX to whatever connector your antenna has (I use 50mm ordered from Aliexpress and normal SMA)

How to program the firmware is described in the [firmware repository](https://github.com/Alex9779/LoFence_Firmware).