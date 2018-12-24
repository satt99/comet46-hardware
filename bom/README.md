# Parts list
Parts required for the Comet46 Keyboard

## Keyboard

Line | Description | Quantity | Links
--- | --- | --- | ---
1 | Comet46 Keyboard PCB | 2 | [files](https://github.com/satt99/comet46-hardware/tree/master/gerbers/keyboard-pcb)
2 | Comet46 PCB plate top | 2 | [files](https://github.com/satt99/comet46-hardware/tree/master/gerbers/pcb-plate-top)
3 | Comet46 PCB plate bottom | 2 | [files](https://github.com/satt99/comet46-hardware/tree/master/gerbers/pcb-plate-bot)
4 | MDBT40-256RV3 nRF51822 | 2 | [seeedstudio](https://www.seeedstudio.com/MDBT40-256RV3-nRF51822-based-BLE-module-p-2503.html), [eleshop](http://eleshop.jp/shop/g/gGAB314/)
5 | Si2302 (or any other pin-compatible low voltage nFET) | 2 | [digikey](https://www.digikey.com/product-detail/en/vishay-siliconix/SI2302CDS-T1-E3/SI2302CDS-T1-E3CT-ND/3305362), [marutsu](https://www.marutsu.co.jp/pc/i/1008871/)
6 | Right angle 0.1" header (for optional programming header) | 2x 4pin |  
7 | CR2032 Battery | 2 | 
8 | CR2032BOX (used the minus side pins to hold the battery) or any kind of conductor that can hold the battery| 2 | [marutsu](https://www.marutsu.co.jp/pc/i/5849/)
9 | CSS-1210MC (Low profile SPDT slide switch) | 2 | [digikey](https://www.digikey.jp/product-detail/ja/nidec-copal-electronics/CSS-1210MC/563-1090-ND/1124205), [marutsu](https://www.marutsu.co.jp/pc/i/600847/#item_description)
10| FC-135 (or any other pin-compatible 32.768kHz crystal) | 2 | [digikey](https://www.digikey.jp/product-detail/ja/epson/FC-135-32.7680KA-A0/SER4077CT-ND/5604233), [marutsu](https://www.marutsu.co.jp/pc/i/16181987/)
11 | 0603 (1608 meteric) SMD 1uF capacitor | 2 | 
12 | 0603 (1608 meteric) SMD 12pF capacitor | 4 | 
13 | Cherry MX or compatible switches | 46 |
14 | Keycaps | 44x 1U + 2x 1.5U| 


## LED-Receiver
Line | Description | Quantity | Links
--- | --- | --- | ---
1 | Receiver Interface PCB | 1 | [files](https://github.com/satt99/comet46-hardware/tree/master/gerbers/ledreceiver) 
2 | MDBT40-256RV3 nRF51822 | 1 | [seeedstudio](https://www.seeedstudio.com/MDBT40-256RV3-nRF51822-based-BLE-module-p-2503.html), [eleshop](http://eleshop.jp/shop/g/gGAB314/)
3 | Pro Mirco | 1 | 
4 | Cree CLVBA-FKA (or any other pin-compatible PLCC-4 LED) | 1 | [digikey](https://www.digikey.com/product-detail/en/cree-inc/CLVBA-FKA-CAEDH8BBB7A363/CLVBA-FKA-CAEDH8BBB7A363CT-ND/2650500), [marutsu](https://www.marutsu.co.jp/pc/i/16173639/)
5 | 1117 3.3v regulator in SOT223 (many types available) | 1 | [digikey](https://www.digikey.com/product-detail/en/diodes-incorporated/AZ1117IH-3.3TRG1/AZ1117IH-3.3TRG1DICT-ND/5699682), [marutsu](https://www.marutsu.co.jp/pc/i/16140973/)
6 | 1206 4.7k resistor array | 2 | [digikey](https://www.digikey.com/product-detail/en/stackpole-electronics-inc/RAVF164DJT4K70/RAVF164DJT4K70CT-ND/2425255), [marutsu](https://www.marutsu.co.jp/pc/i/15932029/)
7 | SMD tactile button (many compatible) | 2 | [digikey](https://www.digikey.com/product-detail/en/c-k/PTS525SM15SMTR2-LFS/CKN9104CT-ND/1146923), [marutsu](https://www.marutsu.co.jp/pc/i/16171690/)
8 | Right angle 0.1" header (for optional programming header) | 1x 4pin | 
9 | Straight 0.1" header (for stacking boards) | 2x 6pin | 
10| FC-135 (or any other pin-compatible 32.768kHz crystal) | 2 | [digikey](https://www.digikey.jp/product-detail/ja/epson/FC-135-32.7680KA-A0/SER4077CT-ND/5604233), [marutsu](https://www.marutsu.co.jp/pc/i/16181987/)
11 | 0603 (1608 meteric) SMD 1uF capacitor | 1 | 
12 | 0603 (1608 meteric) SMD 12pF capacitor | 2 | 


## OLED-Display-Receiver
Line | Description | Quantity | Links | Reference
--- | --- | --- | --- | ---
1 | Receiver Interface PCB | 1 | [files](https://github.com/satt99/comet46-hardware/tree/master/gerbers/oled-display-receiver) | 
2 | MDBT40-256RV3 nRF51822 | 1 | [seeedstudio] (https://www.seeedstudio.com/MDBT40-256RV3-nRF51822-based-BLE-module-p-2503.html), [eleshop](http://eleshop.jp/shop/g/gGAB314/) | U1
3 | ATMEGA32U4-AUR | 1 |  | U2
4 | USB male type A connector | 1 | [akizuki](http://akizukidenshi.com/catalog/g/gC-02236/) | J1
5 | SSD1306 128x32 (OLED display module) | 1 | [yushakobo](https://yushakobo.jp/shop/oled/) | J3
6 | 1206 (3216 meteric) Polyfuse | 1 | [akizuki](http://akizukidenshi.com/catalog/g/gP-13490/) | F1
7 | 0603 (1608 meteric) Schottky diode | 1 | [akizuki](http://akizukidenshi.com/catalog/g/gI-01370/) | D1
8 | 1210 (3225 metric) 16MHz crystal | 1 | [akizuki](http://akizukidenshi.com/catalog/g/gP-02457/) | Y1
9 | 3.3v regulator in SOT23 | 1 | [akizuki](http://akizukidenshi.com/catalog/g/gI-11360/) | U3
10 | Straight 0.1" header (for stacking OLED board & programming MDBT40) | 2 | 1x4pin | | J2 & J3
11 | 0603 (1608 meteric) SMD 0.1uF capacitor | 1 | | C6
12 | 0603 (1608 meteric) SMD 1uF capacitor | 4 | | C3, C4, C5, C7
13 | 0603 (1608 meteric) SMD 12pF capacitor | 2 | | C1, C2
14 | 0603 (1608 meteric) SMD 22ohm resistor | 2 | | R4, R5
15 | 0603 (1608 meteric) SMD 2.4kohm resistor | 1 | | R2
16 | 0603 (1608 meteric) SMD 4.7kohm resistor | 1 | | R3
17 | 0603 (1608 meteric) SMD 10kohm resistor | 1 | | R1
18 | SMD tactile button (many compatible) | 1 | [akizuki](http://akizukidenshi.com/catalog/g/gP-06185/) | SW1