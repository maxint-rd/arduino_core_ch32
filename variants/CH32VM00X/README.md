## CH32VM00X Boards ##

Currently available board variants:
|        |  QFN32 |QSOP24|QFN20|[TSSOP20](#tssop20-pinout) |SSOP16|QFN12|SOP8 |
|--------|--------|------|-----|--------|------|-----|-----|
|CH32V002|_n/a_   |_n/a_ |     |**F4P6**|      |     |     |
|CH32V004|_n/a_   |_n/a_ |     |        |_n/a_ |_n/a_|_n/a_|
|CH32V005|_n/a_   |      |     |        |_n/a_ |     |_n/a_|
|CH32V006|**K8U6**|      |     |**F6P6**|_n/a_ |_n/a_|_n/a_|

------------------

### TSSOP20 PINOUT ###
Arduino pin numbers D0-D17, A0-A7.
Shared pinout for CH32V003F4P6 /CH32V002F4P6/CH32V006F8P6

```
                +-----v-----+
      A7 D14~ 1-+PD4     PD3+-20  D13~ A4
   TX/A5 D15~ 2-+PD5     PD2+-19  D12~ A3
   RX/A6 D16~ 3-+PD6     PD1+-18  D11 SWIO
     RST D17  4-+PD7     PC7+-17  D9  MISO
      A1 D0~  5-+PA1     PC6+-16  D8  MOSI
      A0 D1~  6-+PA2     PC5+-15  D7  SCK
         GND  7-+VSS     PC4+-14  D6~ A2
         D10  8-+PD0     PC3+-13  D5
         VCC  9-+VDD     PC2+-12  D4  SCL
         D2  10-+PC0     PC1+-11  D3  SDA
                +-----------+        
```

### Feature comparison with V003 (TSSOP20) ###

| Feature | V003   | V002   | V004   | V005   | V006   |
| ------- | ------ | ------ | ------ | ------ | ------ |
| Flash   | 16KB   | 16KB   | 32KB   | 32KB   | 62KB   |
| RAM     | 2KB    | 4KB    | 6KB    | 6KB    | 8KB    |
| UserMem | 64B    | 256B   | 256B   | 256B   | 256B   |
| ADC     | 10-bit | 12-bit | 12-bit | 12-bit | 12-bit |
| OPA     | 1-ch   |        |        | 1-ch   | 3-ch   |
| Touch   |        |        |        |        | 8x     |
| Serial  | 1x     | 1x     | 1x     | 1x     | 2x     |
| Timers  | 2+2 WD | 2+2 WD | 2+2 WD | 2+2 WD | 3+2 WD |
| VCC     | 2v7~5v5| 2~5V   | 2~5V   | 2~5V   | 2~5V   |
| ISA     | RV32EC | RV32EmC| RV32EmC| RV32EmC| RV32EmC|

### Documentation ###
- Datasheets: [CH32V002](https://www.wch-ic.com/downloads/CH32V002DS0_PDF.html), [CH32V004](https://www.wch-ic.com/downloads/CH32V004DS0_PDF.html), [CH32V005/CH32V006](https://www.wch-ic.com/downloads/CH32V006DS0_PDF.html)
- Reference manual: [CH32V00X](https://www.wch-ic.com/downloads/CH32V00XRM_PDF.html)
