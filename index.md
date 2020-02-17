---
title: Access control system reference
datatable: true
---
## An Access Control System Reference

This is a quick reference you can use to identify what access control system someone is using simply by looking at a reader.
Keep in mind this reference is user contributed, so information may be missing in the majority of cases. If you could contribute on GitHub, it would be appreciated.

### Readers

<div class="datatable-begin"></div>

Image | Details | Card Technologies | Communication Interface | Countries | Further Information |
----- | ------- | ----------------- | ----------------------- | --------- | ------------------- |
&nbsp; ![hid prox reader](assets/proxpointplus_blk_6005_6008.png) | [HID Global](https://www.hidglobal.com/) <br/> [HID® Proximity ProxPoint® Plus 6005](https://www.hidglobal.com/products/readers/hid-proximity/6005) | 125 kHz <br/> [HID Proximity](https://www.hidglobal.com/products/cards-and-credentials/hid-proximity) | Wiegand | NZ AU | [Proxmark Commands for HID](https://scund00r.com/all/rfid/2018/06/05/proxmark-cheatsheet.html#hidproxcard) <br/> Often contains a small branding strip replacing the HID branding in the center of the reader.
&nbsp; ![cardax reader](assets/cardax-rfid-reader.jpg) | [Cardax Prox Reader](assets/Cardax - Product List April 03.pdf) <br/> [Cardax (Now Gallagher)](https://security.gallagher.com/) | 125 kHz <br/> [Cardax IV](https://www.sourcesecurity.com/datasheets/gallagher-prox-125-khz/co-15214-ga/Gallagher-prox_readers_125.pdf) | Wiegand | NZ AU | Proxmark Commands for Gallagher: <br/> `lf gallagher help` <br/> `lf gallagher demod` <br/> `lf gallagher clone [h] [b <raw hex>]` <br/> Information and high resolution product images are hard to find post the rebranding to Gallagher. <br/> Branded with "Cardax" and "125".
&nbsp; ![cardax reader](assets/cardax-rfid-reader-teardrop.jpg) | [Cardax Prox Reader](assets/Cardax - Product List April 03.pdf) <br/> [Cardax (Now Gallagher)](https://security.gallagher.com/) | 125 kHz <br/> [Cardax IV](https://www.sourcesecurity.com/datasheets/gallagher-prox-125-khz/co-15214-ga/Gallagher-prox_readers_125.pdf) | Wiegand | NZ AU | Proxmark Commands for Gallagher: <br/> `lf gallagher help` <br/> `lf gallagher demod` <br/> `lf gallagher clone [h] [b <raw hex>]`
&nbsp; ![Cardax Prox Plus 125](assets/cardex.jpg) | [Cardax Prox Plus 125](https://usermanual.wiki/Gallagher-Group/19087Y/html) <br/> [Cardax (Now Gallagher)](https://security.gallagher.com/) | 125 kHz <br/> [Cardax IV](https://www.sourcesecurity.com/datasheets/gallagher-prox-125-khz/co-15214-ga/Gallagher-prox_readers_125.pdf) | Wiegand | NZ | Proxmark Commands for Gallagher: <br/> `lf gallagher help` <br/> `lf gallagher demod` <br/> `lf gallagher clone [h] [b <raw hex>]`
&nbsp; ![hid iclass rw100](assets/r10_blk_6100_6108_6109_2.png) | [HID Global](https://www.hidglobal.com/) <br/> [HID® iCLASS® RW100 Reader/Writer 6101](https://www.hidglobal.com/products/readers/iclass/rw100) | 13.56 MHz <br/> [HID iClass](https://www.hidglobal.com/products/cards-and-credentials/iclass) <br/> MIFARE Classic <br/> MIFARE DESFire EV1/EV2 <br/>  | Wiegand | NZ AU | [Proxmark Commands for HID iClass](https://github.com/Proxmark/proxmark3/wiki/commands#hf-iclass) <br/> [HID iClass global key](https://ss23.github.io/hid-iclass-key/) <br/> Very similar appearance to HID iClass SE.
&nbsp; ![hid iclass se](assets/iclass-se-r10.png) | [HID Global](https://www.hidglobal.com/) <br/> [HID® iCLASS SE® R10](https://www.hidglobal.com/products/readers/iclass-se/r10) | 13.56 MHz <br/> iCLASS SE <br/> [HID iClass](https://www.hidglobal.com/products/cards-and-credentials/iclass) <br/> [HID iClass SE](https://www.hidglobal.com/products/readers/iclass-se) <br/> [HID iClass Seos](https://www.hidglobal.com/products/cards-and-credentials/iclass-seos) <br/> MIFARE Classic <br/> MIFARE DESFire EV1 | Wiegand | NZ AU | [Proxmark Commands for iClass](https://scund00r.com/all/rfid/2018/06/05/proxmark-cheatsheet.html#iclass) <br/> [Proxmark Commands for MIFARE Classic](https://scund00r.com/all/rfid/2018/06/05/proxmark-cheatsheet.html#mifare) <br/> Very similar appearance to HID iClass standard. May contain additional branding of "SE".
&nbsp; ![gallagher t20](assets/t20.png) | [Gallagher Security](https://security.gallagher.com/) <br/> [T20 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | 13.56 MHz <br/> MIFARE Classic <br/> MIFARE DESFire EV1/EV2 <br/> 125 kHz <br/> [Cardax IV](https://www.sourcesecurity.com/datasheets/gallagher-prox-125-khz/co-15214-ga/Gallagher-prox_readers_125.pdf) <br/> Bluetooth | RS-485 (HBus and GBus) | NZ AU | [Proxmark Commands for MIFARE Classic](https://scund00r.com/all/rfid/2018/06/05/proxmark-cheatsheet.html#mifare)<br/> May be used as an alarm terminal only, or access control and an alarm system <br/> Many options may be disabled or enabled based on backwards compatibility and security requirements <br/> Backward compatibility for Cardax IV data format. <br/> [Gallagher T-Series Information PDF](https://security.gallagher.com/assets/2523/T-Series_Reader_Datasheet.pdf)
&nbsp; ![gallagher t12](assets/gallagher-t15.jpg) | [Gallagher Security](https://security.gallagher.com/) <br/> [T15 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | Identical to T20 | RS-485 (HBus and GBus) | NZ AU | Identical to T20 in most aspects except alarm functionality
&nbsp; ![gallagher t12](assets/gallagher-t12.jpg) | [Gallagher Security](https://security.gallagher.com/) <br/> [T12 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | Identical to T20 | RS-485 (HBus and GBus)  | NZ AU | Identical to T20 in most aspects except alarm functionality
&nbsp; ![gallagher t11](assets/gallagher-t11.jpg) | [Gallagher Security](https://security.gallagher.com/) <br/> [T11 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | Identical to T20 | RS-485 (HBus and GBus)  | NZ AU | Identical to T20 in most aspects except alarm functionality
&nbsp; ![gallagher t10](assets/gallagher-t10.gif) | [Gallagher Security](https://security.gallagher.com/) <br/> [T10 - T-Series Readers](https://security.gallagher.com/products/t-series-readers) | Identical to T20 | RS-485 (HBus and GBus)  | NZ AU | Identical to T20 in most aspects except alarm functionality
&nbsp; ![paradox R910](assets/Paradox-R910.png) | [Paradox](http://www.paradox.com/) <br/> [R910 (formerly DGP-R910)](http://www.paradox.com/Products/default.asp?CATID=7&SUBCATID=73&PRD=243) | 125 kHZ <br/> Paradox | RS-485 | NZ | [Proxmark Commands for Paradox](https://github.com/Proxmark/proxmark3/wiki/commands#lf-paradox)
&nbsp; ![InnerRange SIFER](assets/innerrange-sifer.png) | [InnerRange SIFER RS-485](https://www.innerrange.com/pd/Card-Readers-Cards/Integriti-Readers/SIFER-Reader) | 13.56 Mhz <br/> MIFARE DESFire EV1/EV2 | RS-485 <br/> Wiegand | NZ |
&nbsp; ![HID Indala Classic](assets/HID-FP3511A.png) | [HID Indala](https://www.hidglobal.com/products/readers/indala/603) | 125 kHz <br/> [FlexSecur](https://www.hidglobal.com/sites/default/files/indala-flexsecur-wp-en.pdf) | Wiegand | NZ | [Proxmark Commands for HID Indala](https://scund00r.com/all/rfid/2018/06/05/proxmark-cheatsheet.html#indala)
&nbsp; ![HID Indala ASR-503](assets/Indala-ASR-503.png) | [HID Indala Mullion SlimLine](https://www.hidglobal.com/products/readers/indala/asr-503) | 125 kHz <br/> [FlexSecur](https://www.hidglobal.com/sites/default/files/indala-flexsecur-wp-en.pdf)| Wiegand | NZ | [Proxmark Commands for HID Indala](https://scund00r.com/all/rfid/2018/06/05/proxmark-cheatsheet.html#indala)
&nbsp; ![PRX-TSEC-STD](assets/PRX-TSEC-STD.png) | [ICT TSEC](https://www.ict.co/TSEC-Standard-Card-Reader) | 13.56 Mhz <br/> MIFARE DESFire EV1/EV2 <br/> 125 kHz | RS-485 <br/> Wiegand | NZ AU | Some models are LF (125 kHz) only. <br/> Some models have a keypad. <br/> [Full list of models available](https://www.ict.co/Proximity-Products).
&nbsp; ![GE reader](assets/GE.jpg) | GE (General Electric) | Unknown | Unknown | AU |
&nbsp; ![unknown reader](assets/unknown1.jpg) | GE (General Electric) | Unknown | Unknown | NZ |
&nbsp; ![unknown reader](assets/unknown2.jpg) | GE (General Electric) | Unknown | Unknown | NZ |


### Cards and Key Fobs

Some access cards are clearly branded and marked, making them easy to identify. It is much harder to identify a HF (13.56 MHz) access card or key fob without proxmark, as they almost all look the same.

Image | Details |
----- | ------- |
&nbsp; ![HID Prox II Card](assets/HID-Prox-II-card.jpg) | HID Prox II Card |
&nbsp; ![HID Prox II Key Fob](assets/HID-Prox-II-dongle.jpg) | HID Prox II Key Fob |
&nbsp; ![HID iClass Key Fob](assets/HID-iClass-dongle.jpg) | HID iClass Key Fob |
&nbsp; ![HID Indala Key Fob](assets/HID-Indala-dongle.png) | HID Indala Key Fob |
&nbsp; ![HID Indala Card](assets/HID-Indala-card.jpg) | HID Indala Card |
&nbsp; ![InnerRange SIFER Card](assets/innerrange-sifer-card.jpg) | InnerRange SIFER Card |


<div class="datatable-end"></div>

### Contributing

Any contributions, especially making the front-end nicer or information on access control systems in your country, are much appreciated. Please send a pull request on GitHub and the website will be updated automatically when the information is merged.
