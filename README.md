# CFAF240320A0-024Sx  

This example Seeeduino (Arduino Uno clone) software cane be used with any of the displays in our CFAF240320A0-024Sx family. The family includes:

[Crystalfontz CFAF240320A0-024SN.  
This display is a 2.4in 240x320 TFT.  
](https://www.crystalfontz.com/product/cfaf240320a0024sn-240x320-sunlight-readable-tft)

[Crystalfontz CFAF240320A0-024SC.  
This display is a 2.4in 240x320 TFT with a capacitive touch panel.  ](https://www.crystalfontz.com/product/cfaf240320a0024sc-240x320-full-color-touchscreen-tft-2-4)

[Crystalfontz CFAF240320A0-024SR.  
This display is a 2.4in 240x320 TFT with a resistive touch panel.  ](https://www.crystalfontz.com/product/cfaf240320a0024sr-240x320-resistive-touchscreen-tft-display)

To change the expected type of touch, update line 110 of CFAF240320A0-024Sx.ino to define the touch type that matches your display.


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

| Cap Touch  Pin  | Seeeduino Pin| Connection Description |
|-----------------|--------------|------------------------|
| 1 (GND)         | GND          | Ground                 |
| 2 (RESET)       | 2            | TP Reset               |
| 3 (INT)         | 3            | TP Interrupt           |
| 4 (SDA)         | SDA          | I2C Data               |
| 5 (SCL)         | SCL          | I2C Clock              |
| 6 (VDD)         |              | +3.3V Power            |

| Res Touch  Pin  | Seeeduino Pin| Connection Description |
|-----------------|--------------|------------------------|
| 1 (XL)          |   D14/A0     | TP Left                |
| 2 (YD)          |   D16/A2     | TP Down                |
| 3 (XR)          |   D15/A1     | TP Right               |
| 4 (YU)          |   D17/A3     | TP Up                  |


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

## CFA10102 Bring Up Board
This display is compaible with our [CFA10102 generic bring up board](https://www.crystalfontz.com/product/cfa10102-oled-breakout-board). 

