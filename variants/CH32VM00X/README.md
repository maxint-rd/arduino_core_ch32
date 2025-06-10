## CH32VM00X ##
CH32 V002, V004, V005, V006

### TSSOP20 PINOUT ###
Arduino pin numbers 0-14, A0-A7.
Shared pinout for CH32V003F4P6 /CH32V002F4P6/CH32V006F8P6

```
            +-----v-----+
   14/A7 1 -+PD4     PD3+- 20  13/A4
   TX/A5 2 -+PD5     PD2+- 19  12/A3
   RX/A6 3 -+PD6     PD1+- 18  SWIO
     RST 4 -+PD7     PC7+- 17  9
    0/A1 5 -+PA1     PC6+- 16  8
    1/A0 6 -+PA2     PC5+- 15  7
     GND 7 -+VSS     PC4+- 14  6/A2
      10 8 -+PD0     PC3+- 13  5
     VCC 9 -+VDD     PC2+- 12  4/SCL
      2 10 -+PC0     PC1+- 11  3/SDA
            +-----------+        
```

### Feature comparison with V003 (TSSOP20) ###

| Feature | V003   | V002   | V006   |
| ------- | ------ | ------ | ------ |
| Flash   | 16KB   | 16KB   | 62KB   |
| RAM     | 2KB    | 4KB    | 8KB    |
| UserMem | 64B    | 256B   | 256B   |
| ADC     | 10-bit | 12-bit | 12-bit |
| OPA     | 1-ch   |        | 3-ch   |
| Touch   |        |        | 8x     |
| Serial  | 1x     | 1x     | 2x     |
| Timers  | 2+2 WD | 2+2 WD | 3+2 WD |
| VCC     | 2v7~5v5| 2~5V   | 2~5V   |
| ISA     | RV32EC | RV32EmC| RV32EmC|


------------------
