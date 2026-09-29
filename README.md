# Schematic

## Parts List

- [capacitors](https://www.digikey.com.au/en/products/detail/nextgen-components/0402W105M6R3HI/18677006) 
	- 10nF: [0402B103K500HI](https://www.digikey.com.au/en/products/detail/nextgen-components/0402B103K500HI/22601905)
	- 0.1uF: [0402B104K250HI](https://www.digikey.com.au/en/products/detail/nextgen-components/0402B104K250HI/14670955)
	- 1uF: [0402W105M6R3HI](https://www.digikey.com.au/en/products/detail/nextgen-components/0402W105M6R3HI/18677006), 
	- 4.7uF: [0402W475M6R3HI](https://www.digikey.com.au/en/products/detail/nextgen-components/0402W475M6R3HI/18677043)
	- 10uF: [0402W106M6R3HI](https://www.digikey.com.au/en/products/detail/nextgen-components/0402W106M6R3HI/18677011)
	- footprint: 0402
	- 220uF electrolytic: [Wurth Elektronik 865080245009](https://www.digikey.com.au/en/products/detail/w%C3%BCrth-elektronik/865080245009/5728087?s=N4IgTCBcDaIBwDYCsAGOKwBZUoJwgF0BfIA)
	- footprint: 6.6 (dia) x 7.7 (height)
- LEDs: [green](https://www.digikey.com.au/en/products/detail/xinglight/XL-1608PGC-06/25673192) | [red](https://www.digikey.com.au/en/products/detail/xinglight/XL-1608VRC-06/25673309)
	- green: XL-1608PGC-06
    - red: XL-1608VRC-06
	- footprint: 0603
- [schottky diode](PMEG2015EH,115):
	- PMEG2015EH,115
- resistors (CR0603)
	- 330: [CR0603-FX-3300ELF](https://www.digikey.com.au/en/products/detail/bourns-inc/CR0603-FX-3300ELF/3783948)
	- 3.3k: [CR0603-JW-332ELF](https://www.digikey.com.au/en/products/detail/bourns-inc/CR0603-JW-332ELF/3784358)
	- 5.1k: [CR0603-FX-5101ELF](https://www.digikey.com.au/en/products/detail/bourns-inc/CR0603-FX-5101ELF/3784064)
	- 10k: [CR0603-FX-1002ELF](https://www.digikey.com.au/en/products/detail/bourns-inc/CR0603-FX-1002ELF/3593188)
	- 100k: [CR0603-FX-1003ELF](https://www.digikey.com.au/en/products/detail/bourns-inc/CR0603-FX-1003ELF/3593193)
- [push button](https://www.digikey.com.au/en/products/detail/c-k/PTS636SK25SMTR-LFS/10071735)
	- PTS636SK25SMTR LFS
- [usb receptacle](https://au.mouser.com/en/ProductDetail/Same-Sky/UJ20-C-H-G-SMT-1-P16-TR)
	- 179-UJ20CHGSMT1P16TR
- JST PH2.0 connector
- IRLML6402
- APK2112K-3.3
- MCP73831-2-OT
- ESP32-S3-WROOM-1-N16R8

## GPIO Connections

| Function   | ESP32-S3 GPIO |
| ---------- | ------------- |
| OLED_SDA   | 10            |
| OLED_SCL   | 9             |
| MIC_SCK    | 5             |
| MIC_WS     | 6             |
| MIC_SD     | 7             |
| ENCODER_A  | 14            |
| ENCODER_B  | 13            |
| ENCODER_SW | 12            |
| LED_DATA   | 16            |


