# CFAF240320A0-024SC  

Crystalfontz CFAF240320A0-024SC.  
This display is a 2.4in 240x320 TFT with a capacitive touch panel.  

Example Seeeduino (Arduino clone) software.   
  
This product can be found here:  
https://www.crystalfontz.com/product/cfaf240320a0024sc

## Connection Details

|  LCD Pin   | Seeeduino Pin|    Connection Description    |
|------------|--------------|------------------------------|
| 1 (LED-A)  |              | LED Power (Approx 9V @ 40mA) |
| 2 (LED-K)  |              | LED Ground                   |
| 3 (IOVCC)  |              | +3.3V Power                  |
| 24 (SDA)   | 11           | LCD MOSI                     |
| 25 (GND)   | GND          | Ground                       |
| 27 (GND)   | GND          | Ground                       |
| 32 (WRB)   | 8            | LCD R/S                      |
| 33 (RS)    | 13           | LCD SCK                      |
| 34 (CSB)   | 10           | LCD CS                       |
| 35 (RESET) | 9            | LCD Reset                    |
| 36 (IM0)   | GND          | Ground                       |
| 37 (IM1)   |              | +3.3V Power                  |
| 38 (IM2)   |              | +3.3V Power                  |
| 39 (VCI)   |              | +3.3V Power                  |
| 40 (GND)   | GND          | Ground                       |

| Touch Panel Pin | Seeeduino Pin| Connection Description |
|-----------------|--------------|------------------------|
| 1 (GND)         | GND          | Ground                 |
| 2 (RESET)       | 2            | TP Reset               |
| 3 (INT)         | 3            | TP Interrupt           |
| 4 (SDA)         | SDA          | I2C Data               |
| 5 (SCL)         | SCL          | I2C Clock              |
| 6 (VDD)         |              | +3.3V Power            |

## Micro SD Connection Details

A micro SD Adapter Board can be found here: https://www.crystalfontz.com/product/cfa10112

| microSD Pin | Seeeduino Pin| Connection Description |
|-------------|--------------|------------------------|
| 2 (CS)      | 7            | SD CS                  |
| 3 (DI)      | 11           | SD MOSI                |
| 4 (VDD)     |              | +3.3V Power            |
| 5 (SCLK)    | 13           | SD SCLK                |
| 6 (VSS)     | GND          | Ground                 |
| 7 (DO)      | 12           | SD MISO                |

(microSD connection is optional)
