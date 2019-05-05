---
title: Access control system reference
datatable: true
---
## An access control system reference

This is a quick reference you can use to identify what access control system someone is using simply by looking at a reader.
Keep in mind this reference is user contributed, so information may be missing in the majority of cases. If you could contribute on GitHub, it would be appreciated.

### Readers

<div class="datatable-begin"></div>

Image                                                                              | Details                                   | Card Types                                                                                        | Countries    | Further Information
---------------------------------------------------------------------------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------ | -------------------
&nbsp; ![hid prox reader](assets/proxpointplus_blk_6005_6008.png)                  | [HID Global](https://www.hidglobal.com/) <br/> [HID® Proximity ProxPoint® Plus 6005](https://www.hidglobal.com/products/readers/hid-proximity/6005)  | 125 kHz - [HID Proximity](https://www.hidglobal.com/products/cards-and-credentials/hid-proximity) | NZ AU           | [Proxmark Commands for HID Proximity](https://github.com/Proxmark/proxmark3/wiki/commands#lf-hid) <br/>Often contains a small branding strip replacing the HID branding in the center of the reader
&nbsp; ![cardax reader](assets/cardax-rfid-reader.jpg) | [Cardax (Now Gallagher)](https://security.gallagher.com/) <br>[Cardax Prox Reader](assets/Cardax - Product List April 03.pdf) | 125 kHz - [HID Proximity](https://www.hidglobal.com/products/cards-and-credentials/hid-proximity) | NZ AU | [Proxmark Commands for HID Proximity](https://github.com/Proxmark/proxmark3/wiki/commands#lf-hid) <br/> Information and high resolution product images are hard to find post the rebranding to Gallagher. <br/>Branded with "Cardax" and "125"
&nbsp; ![cardax Prox Mifare](assets/cardex.jpg) | [Cardax (Now Gallagher)](https://security.gallagher.com/) <br>[Cardax Prox Mifare Reader](assets/Cardax - Product List April 03.pdf) | 125 kHz and 13.56 MHz | NZ | <br/> Information and high resolution product images are hard to find post the rebranding to Gallagher.
&nbsp; ![hid iclass rw100](assets/r10_blk_6100_6108_6109_2.png) | [HID Global](https://www.hidglobal.com/) <br/> [HID® iCLASS® RW100 Reader/Writer 6101](https://www.hidglobal.com/products/readers/iclass/rw100) | 13.56 MHz - [HID iClass](https://www.hidglobal.com/products/cards-and-credentials/iclass) <br/> System may include backwards compatibility for MIFARE (classic or DESFire) or HID Proximity | NZ AU     | Very similar appearance to HID iClass SE <br/> [Proxmark Commands for HID iClass](https://github.com/Proxmark/proxmark3/wiki/commands#hf-iclass) <br/> [HID iClass global key](https://ss23.github.io/hid-iclass-key/)
&nbsp; ![hid iclass se](assets/iclass-se-r10.png) | [HID Global](https://www.hidglobal.com/) <br/> [HID® iCLASS SE® R10](https://www.hidglobal.com/products/readers/iclass-se/r10) | 13.56 MHz - [HID iClass](https://www.hidglobal.com/products/cards-and-credentials/iclass) <br/> [HID iClass SE](https://www.hidglobal.com/products/readers/iclass-se) <br/> May contain backwards compatibility for MIFARE (classic or DESFire) or HID Proximity | NZ AU    | Very similar appearance to HID iClass standard. May contain additional branding of "SE" <br/>[Proxmark Commands for HID iClass](https://github.com/Proxmark/proxmark3/wiki/commands#hf-iclass)
&nbsp; ![gallagher t20](assets/t20.png) | [Gallagher Security](https://security.gallagher.com/) <br/>[T20 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | 13.56 Mhz - MIFARE DESFire EV1, MIFARE DESFire EV2, MIFARE Plus and MIFARE Classic<br/>125 kHZ - [HID Proximity](https://www.hidglobal.com/products/cards-and-credentials/hid-proximity) <br/> Bluetooth | NZ AU | May be used as an alarm terminal only, or access control and an alarm system <br/> Many options may be disabled or enabled based on backwards compatibility and security requirements <br/>[Gallagher T-Series Information PDF](https://security.gallagher.com/assets/2523/T-Series_Reader_Datasheet.pdf)
&nbsp; ![gallagher t12](assets/gallagher-t12.jpg) | [Gallagher Security](https://security.gallagher.com/) <br/>[T12 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | Identical to T20 | NZ AU | Identical to T20 in most aspects except alarm functionality
&nbsp; ![gallagher t11](assets/gallagher-t11.gif) | [Gallagher Security](https://security.gallagher.com/) <br/>[T11 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | Identical to T20 | NZ AU | Identical to T20 in most aspects except alarm functionality
&nbsp; ![gallagher t10](assets/gallagher-t10.gif) | [Gallagher Security](https://security.gallagher.com/) <br/>[T10 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | Identical to T20 | NZ AU | Identical to T20 in most aspects except alarm functionality
&nbsp; ![paradox R910](assets/Paradox-R910.png) | [Paradox](http://www.paradox.com/)<br/> [R910 (formerly DGP-R910)](http://www.paradox.com/Products/default.asp?CATID=7&SUBCATID=73&PRD=243) | 125 kHZ - Paradox | NZ | [Proxmark Commands for Paradox](https://github.com/Proxmark/proxmark3/wiki/commands#lf-paradox)
&nbsp; ![GE reader](assets/GE.jpg) | GE (General Electric) | Unknown | AU | 
&nbsp; ![unknown reader](assets/unknown1.jpg) | GE (General Electric) | Unknown | NZ | 
&nbsp; ![unknown reader](assets/unknown2.jpg) | GE (General Electric) | Unknown | NZ | 

<div class="datatable-end"></div>

### Contributing

Any contributions, especially making the front-end nicer or information on access control systems in your country, are much appreciated. Please send a pull request on GitHub and the website will be updated automatically when the information is merged.
