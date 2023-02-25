
## Compilar o wiringOP

```
# git clone https://github.com/IsmaelValentinLeandro/opi.git
# cd opi
# mkdir wiringOP
# mv wiringOP.zip ./wiringOP
# cd wiringOP
# unzip wiringOP.zip
# sudo ./build clean
# sudo ./build 
# cd ..
# cd ..
# rm -r opi
#
```

---
## The output of the gpio readall command

## Allwinner H2+

### Orange Pi Zero/R1

```
 +------+-----+----------+------+---+  OPi H2  +---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   12 |   0 |    SDA.0 | ALT2 | 0 |  3 || 4  |   |      | 5V       |     |      |
 |   11 |   1 |    SCL.0 | ALT2 | 0 |  5 || 6  |   |      | GND      |     |      |
 |    6 |   2 |    PWM.1 |  OFF | 0 |  7 || 8  | 0 | ALT2 | TXD.1    | 3   | 198  |
 |      |     |      GND |      |   |  9 || 10 | 0 | ALT2 | RXD.1    | 4   | 199  |
 |    1 |   5 |    RXD.2 | ALT2 | 0 | 11 || 12 | 0 | OFF  | PA07     | 6   | 7    |
 |    0 |   7 |    TXD.2 | ALT2 | 0 | 13 || 14 |   |      | GND      |     |      |
 |    3 |   8 |    CTS.2 |  OFF | 0 | 15 || 16 | 0 | ALT3 | SDA.1    | 9   | 19   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | ALT3 | SCK.1    | 10  | 18   |
 |   15 |  11 |   MOSI.1 | ALT2 | 1 | 19 || 20 |   |      | GND      |     |      |
 |   16 |  12 |   MISO.1 | ALT2 | 0 | 21 || 22 | 0 | OFF  | RTS.2    | 13  | 2    |
 |   14 |  14 |   SCLK.1 | ALT2 | 0 | 23 || 24 | 0 | ALT2 | CE.1     | 15  | 13   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PA10     | 16  | 10   |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+  OPi H2  +---+------+----------+-----+------+
```

## Allwinner H3

### Orange Pi Zero Plus 2

```
 +------+-----+----------+------+---+ZEROPLUS 2+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   12 |   0 |    SDA.0 | ALT2 | 0 |  3 || 4  |   |      | 5V       |     |      |
 |   11 |   1 |    SCL.0 | ALT2 | 0 |  5 || 6  |   |      | GND      |     |      |
 |    6 |   2 |      PA6 |  OFF | 0 |  7 || 8  | 0 | ALT2 | TXD.2    | 3   | 0    |
 |      |     |      GND |      |   |  9 || 10 | 0 | ALT2 | RXD.2    | 4   | 1    |
 |  352 |   5 |    S-SCL | ALT2 | 0 | 11 || 12 | 0 | OFF  | PD11     | 6   | 107  |
 |  353 |   7 |    S-SDA | ALT2 | 0 | 13 || 14 |   |      | GND      |     |      |
 |    3 |   8 |    CTS.2 |  OFF | 0 | 15 || 16 | 0 | ALT3 | SDA.1    | 9   | 19   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | ALT3 | SCL.1    | 10  | 18   |
 |   15 |  11 |   MOSI.1 | ALT2 | 0 | 19 || 20 |   |      | GND      |     |      |
 |   16 |  12 |   MISO.1 | ALT2 | 0 | 21 || 22 | 0 | OFF  | RTS.2    | 13  | 2    |
 |   14 |  14 |   SCLK.1 | ALT2 | 0 | 23 || 24 | 0 | ALT2 | CE.1     | 15  | 13   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PD14     | 16  | 110  |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+ZEROPLUS 2+---+------+----------+-----+------+
```

### OrangePi One/Lite/Pc/Plus/PcPlus/Plus2e

```
 +------+-----+----------+------+---+OrangePiH3+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   12 |   0 |    SDA.0 |  OUT | 0 |  3 || 4  |   |      | 5V       |     |      |
 |   11 |   1 |    SCL.0 |  OUT | 0 |  5 || 6  |   |      | GND      |     |      |
 |    6 |   2 |      PA6 |  OUT | 0 |  7 || 8  | 0 | OUT  | TXD.3    | 3   | 13   |
 |      |     |      GND |      |   |  9 || 10 | 0 | OUT  | RXD.3    | 4   | 14   |
 |    1 |   5 |    RXD.2 |  OUT | 0 | 11 || 12 | 0 | OUT  | PD14     | 6   | 110  |
 |    0 |   7 |    TXD.2 |  OUT | 0 | 13 || 14 |   |      | GND      |     |      |
 |    3 |   8 |    CTS.2 |  OUT | 0 | 15 || 16 | 0 | OUT  | PC04     | 9   | 68   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | OUT  | PC07     | 10  | 71   |
 |   64 |  11 |   MOSI.0 |  OUT | 0 | 19 || 20 |   |      | GND      |     |      |
 |   65 |  12 |   MISO.0 |  OUT | 0 | 21 || 22 | 0 | OUT  | RTS.2    | 13  | 2    |
 |   66 |  14 |   SCLK.0 |  OUT | 0 | 23 || 24 | 0 | OUT  | CE.0     | 15  | 67   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OUT  | PA21     | 16  | 21   |
 |   19 |  17 |    SDA.1 |  OUT | 0 | 27 || 28 | 0 | OUT  | SCL.1    | 18  | 18   |
 |    7 |  19 |     PA07 |  OUT | 0 | 29 || 30 |   |      | GND      |     |      |
 |    8 |  20 |     PA08 |  OUT | 0 | 31 || 32 | 0 | OUT  | RTS.1    | 21  | 200  |
 |    9 |  22 |     PA09 |  OUT | 0 | 33 || 34 |   |      | GND      |     |      |
 |   10 |  23 |     PA10 |  OUT | 0 | 35 || 36 | 0 | OUT  | CTS.1    | 24  | 201  |
 |   20 |  25 |     PA20 |  OUT | 0 | 37 || 38 | 0 | OUT  | TXD.1    | 26  | 198  |
 |      |     |      GND |      |   | 39 || 40 | 0 | OUT  | RXD.1    | 27  | 199  |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+OrangePiH3+---+------+----------+-----+------+
```

## Allwinner H5

### Orange Pi Zero Plus

```
 +------+-----+----------+------+---+ ZEROPLUS +---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   12 |   0 |    SDA.0 | ALT2 | 0 |  3 || 4  |   |      | 5V       |     |      |
 |   11 |   1 |    SCL.0 | ALT2 | 0 |  5 || 6  |   |      | GND      |     |      |
 |    6 |   2 |      PA6 |  OFF | 0 |  7 || 8  | 0 | ALT2 | TXD.1    | 3   | 198  |
 |      |     |      GND |      |   |  9 || 10 | 0 | ALT2 | RXD.1    | 4   | 199  |
 |    1 |   5 |    RXD.2 | ALT2 | 0 | 11 || 12 | 0 | OFF  | PA07     | 6   | 7    |
 |    0 |   7 |    TXD.2 | ALT2 | 0 | 13 || 14 |   |      | GND      |     |      |
 |    3 |   8 |    CTS.2 |  OFF | 0 | 15 || 16 | 0 | ALT3 | SDA.1    | 9   | 19   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | ALT3 | SCL.1    | 10  | 18   |
 |   15 |  11 |   MOSI.1 | ALT2 | 0 | 19 || 20 |   |      | GND      |     |      |
 |   16 |  12 |   MISO.1 | ALT2 | 0 | 21 || 22 | 0 | OFF  | RTS.2    | 13  | 2    |
 |   14 |  14 |   SCLK.1 | ALT2 | 0 | 23 || 24 | 0 | ALT2 | CE.1     | 15  | 13   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PA10     | 16  | 10   |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+ ZEROPLUS +---+------+----------+-----+------+
```

### Orange Pi Zero Plus 2

```
 +------+-----+----------+------+---+ZEROPLUS 2+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   12 |   0 |    SDA.0 | ALT2 | 0 |  3 || 4  |   |      | 5V       |     |      |
 |   11 |   1 |    SCL.0 | ALT2 | 0 |  5 || 6  |   |      | GND      |     |      |
 |    6 |   2 |      PA6 |  OFF | 0 |  7 || 8  | 0 | ALT2 | TXD.2    | 3   | 0    |
 |      |     |      GND |      |   |  9 || 10 | 0 | ALT2 | RXD.2    | 4   | 1    |
 |  352 |   5 |    S-SCL | ALT2 | 0 | 11 || 12 | 0 | OFF  | PD11     | 6   | 107  |
 |  353 |   7 |    S-SDA | ALT2 | 0 | 13 || 14 |   |      | GND      |     |      |
 |    3 |   8 |    CTS.2 |  OFF | 0 | 15 || 16 | 0 | ALT3 | SDA.1    | 9   | 19   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | ALT3 | SCL.1    | 10  | 18   |
 |   15 |  11 |   MOSI.1 | ALT2 | 0 | 19 || 20 |   |      | GND      |     |      |
 |   16 |  12 |   MISO.1 | ALT2 | 0 | 21 || 22 | 0 | OFF  | RTS.2    | 13  | 2    |
 |   14 |  14 |   SCLK.1 | ALT2 | 0 | 23 || 24 | 0 | ALT2 | CE.1     | 15  | 13   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PD14     | 16  | 110  |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+ZEROPLUS 2+---+------+----------+-----+------+
```

### Orange Pi Pc 2

```
 +------+-----+----------+------+---+  OPi PC2 +---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   12 |   0 |    SDA.0 | ALT2 | 0 |  3 || 4  |   |      | 5V       |     |      |
 |   11 |   1 |    SCL.0 | ALT2 | 0 |  5 || 6  |   |      | GND      |     |      |
 |    6 |   2 |    PWM.1 |  OFF | 0 |  7 || 8  | 0 | OFF  | PC05     | 3   | 69   |
 |      |     |      GND |      |   |  9 || 10 | 0 | OFF  | PC06     | 4   | 70   |
 |    1 |   5 |    RXD.2 | ALT2 | 0 | 11 || 12 | 0 | OFF  | PD14     | 6   | 110  |
 |    0 |   7 |    TXD.2 | ALT2 | 0 | 13 || 14 |   |      | GND      |     |      |
 |    3 |   8 |    CTS.2 | ALT2 | 0 | 15 || 16 | 0 | OFF  | PC04     | 9   | 68   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | OFF  | PC07     | 10  | 71   |
 |   15 |  11 |   MOSI.1 | ALT2 | 0 | 19 || 20 |   |      | GND      |     |      |
 |   16 |  12 |   MISO.1 | ALT2 | 0 | 21 || 22 | 0 | ALT2 | RTS.2    | 13  | 2    |
 |   14 |  14 |   SCLK.1 | ALT2 | 0 | 23 || 24 | 0 | ALT2 | CE.1     | 15  | 13   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PA21     | 16  | 21   |
 |   19 |  17 |    SDA.1 | ALT3 | 0 | 27 || 28 | 0 | ALT3 | SCL.1    | 18  | 18   |
 |    7 |  19 |     PA07 |  OFF | 0 | 29 || 30 |   |      | GND      |     |      |
 |    8 |  20 |     PA08 |  OFF | 0 | 31 || 32 | 0 | ALT2 | RTS.1    | 21  | 200  |
 |    9 |  22 |     PA09 |  OFF | 0 | 33 || 34 |   |      | GND      |     |      |
 |   10 |  23 |     PA10 |  OFF | 0 | 35 || 36 | 0 | ALT2 | CTS.1    | 24  | 201  |
 |  107 |  25 |     PD11 |  OFF | 0 | 37 || 38 | 0 | ALT2 | TXD.1    | 26  | 198  |
 |      |     |      GND |      |   | 39 || 40 | 0 | ALT2 | RXD.1    | 27  | 199  |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+  OPi PC2 +---+------+----------+-----+------+
```

### Orange Pi Prime

```
 +------+-----+----------+------+---+   PRIME  +---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   12 |   0 |    SDA.0 | ALT2 | 0 |  3 || 4  |   |      | 5V       |     |      |
 |   11 |   1 |    SCL.0 | ALT2 | 0 |  5 || 6  |   |      | GND      |     |      |
 |    6 |   2 |    PWM.1 |  OFF | 0 |  7 || 8  | 0 | OFF  | PC05     | 3   | 69   |
 |      |     |      GND |      |   |  9 || 10 | 0 | OFF  | PC06     | 4   | 70   |
 |    1 |   5 |    RXD.2 | ALT2 | 0 | 11 || 12 | 0 | OFF  | PD14     | 6   | 110  |
 |    0 |   7 |    TXD.2 | ALT2 | 0 | 13 || 14 |   |      | GND      |     |      |
 |    3 |   8 |    CTS.2 | ALT2 | 0 | 15 || 16 | 0 | OFF  | PC04     | 9   | 68   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | OFF  | PC07     | 10  | 71   |
 |   15 |  11 |   MOSI.1 | ALT2 | 0 | 19 || 20 |   |      | GND      |     |      |
 |   16 |  12 |   MISO.1 | ALT2 | 0 | 21 || 22 | 0 | ALT2 | RTS.2    | 13  | 2    |
 |   14 |  14 |   SCLK.1 | ALT2 | 0 | 23 || 24 | 0 | ALT2 | CE.1     | 15  | 13   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PC08     | 16  | 72   |
 |   19 |  17 |    SDA.1 | ALT3 | 0 | 27 || 28 | 0 | ALT3 | SCL.1    | 18  | 18   |
 |    7 |  19 |     PA07 |  OFF | 0 | 29 || 30 |   |      | GND      |     |      |
 |    8 |  20 |     PA08 |  OFF | 0 | 31 || 32 | 0 | OFF  | PC09     | 21  | 73   |
 |    9 |  22 |     PA09 |  OFF | 0 | 33 || 34 |   |      | GND      |     |      |
 |   10 |  23 |     PA10 |  OFF | 0 | 35 || 36 | 0 | OFF  | PC10     | 24  | 74   |
 |  107 |  25 |     PD11 |  OFF | 0 | 37 || 38 | 0 | OFF  | PC11     | 26  | 75   |
 |      |     |      GND |      |   | 39 || 40 | 0 | OFF  | PC12     | 27  | 76   |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+   PRIME  +---+------+----------+-----+------+
```

## Allwinner A64 

### Orange Pi Win/Winplus

```
 +------+-----+----------+------+---+ OPi Win  +---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |  227 |   0 |    SDA.1 | ALT2 | 0 |  3 || 4  |   |      | 5V       |     |      |
 |  226 |   1 |    SCL.1 | ALT2 | 0 |  5 || 6  |   |      | GND      |     |      |
 |  362 |   2 |     PL10 |  OFF | 0 |  7 || 8  | 0 | ALT2 | PL02     | 3   | 354  |
 |      |     |      GND |      |   |  9 || 10 | 0 | ALT2 | PL03     | 4   | 355  |
 |  229 |   5 |    RXD.3 | ALT2 | 0 | 11 || 12 | 0 | OFF  | PD04     | 6   | 100  |
 |  228 |   7 |    TXD.3 | ALT2 | 0 | 13 || 14 |   |      | GND      |     |      |
 |  231 |   8 |    CTS.3 |  OUT | 0 | 15 || 16 | 0 | OFF  | PL09     | 9   | 361  |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | OFF  | PC04     | 10  | 68   |
 |   98 |  11 |   MOSI.1 | ALT4 | 0 | 19 || 20 |   |      | GND      |     |      |
 |   99 |  12 |   MISO.1 | ALT4 | 0 | 21 || 22 | 0 | OFF  | RTS.3    | 13  | 230  |
 |   97 |  14 |   SCLK.1 | ALT4 | 0 | 23 || 24 | 0 | ALT4 | CE.1     | 15  | 96   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PD06     | 16  | 102  |
 |  143 |  17 |    SDA.2 | ALT3 | 0 | 27 || 28 | 0 | ALT3 | SCL.2    | 18  | 142  |
 |   36 |  19 |     PB04 |  OFF | 0 | 29 || 30 |   |      | GND      |     |      |
 |   37 |  20 |     PB05 |  OFF | 0 | 31 || 32 | 0 | ALT2 | RTS.2    | 21  | 34   |
 |   38 |  22 |     PB06 |  OFF | 0 | 33 || 34 |   |      | GND      |     |      |
 |   39 |  23 |     PB07 |  OFF | 0 | 35 || 36 | 0 | ALT2 | CTS.2    | 24  | 35   |
 |  101 |  25 |     PD05 |  OFF | 0 | 37 || 38 | 0 | ALT2 | TXD.2    | 26  | 32   |
 |      |     |      GND |      |   | 39 || 40 | 0 | ALT2 | RXD.2    | 27  | 33   |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+ OPi Win  +---+------+----------+-----+------+
```

## Allwinner H6

### Orange Pi 3/3 LTS

```
 +------+-----+----------+------+---+   OPi 3  +---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |  122 |   0 |    SDA.0 |  OFF | 0 |  3 || 4  |   |      | 5V       |     |      |
 |  121 |   1 |    SCL.0 |  OFF | 0 |  5 || 6  |   |      | GND      |     |      |
 |  118 |   2 |    PWM.0 |  OFF | 0 |  7 || 8  | 0 | OFF  | PL02     | 3   | 354  |
 |      |     |      GND |      |   |  9 || 10 | 0 | OFF  | PL03     | 4   | 355  |
 |  120 |   5 |    RXD.3 | ALT4 | 0 | 11 || 12 | 0 | OFF  | PD18     | 6   | 114  |
 |  119 |   7 |    TXD.3 | ALT4 | 0 | 13 || 14 |   |      | GND      |     |      |
 |  362 |   8 |     PL10 |  OFF | 0 | 15 || 16 | 0 | OFF  | PD15     | 9   | 111  |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | OFF  | PD16     | 10  | 112  |
 |  229 |  11 |   MOSI.1 | ALT2 | 0 | 19 || 20 |   |      | GND      |     |      |
 |  230 |  12 |   MISO.1 | ALT2 | 0 | 21 || 22 | 0 | OFF  | PD21     | 13  | 117  |
 |  228 |  14 |   SCLK.1 | ALT2 | 0 | 23 || 24 | 0 | ALT2 | CE.1     | 15  | 227  |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PL08     | 16  | 360  |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+   OPi 3  +---+------+----------+-----+------+
```

### Orange Pi Lite2/OnePlus

```
 +------+-----+----------+------+---+  OPi H6  +---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |  230 |   0 |    SDA.1 |  OFF | 0 |  3 || 4  |   |      | 5V       |     |      |
 |  229 |   1 |    SCL.1 |  OFF | 0 |  5 || 6  |   |      | GND      |     |      |
 |  228 |   2 |     PWM1 |  OFF | 0 |  7 || 8  | 0 | OFF  | PD21     | 3   | 117  |
 |      |     |      GND |      |   |  9 || 10 | 0 | OFF  | PD22     | 4   | 118  |
 |  120 |   5 |    RXD.3 | ALT4 | 0 | 11 || 12 | 0 | OFF  | PC09     | 6   | 73   |
 |  119 |   7 |    TXD.3 | ALT4 | 0 | 13 || 14 |   |      | GND      |     |      |
 |  122 |   8 |    CTS.3 |  OFF | 0 | 15 || 16 | 0 | OFF  | PC08     | 9   | 72   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | OFF  | PC07     | 10  | 71   |
 |   66 |  11 |   MOSI.0 | ALT4 | 0 | 19 || 20 |   |      | GND      |     |      |
 |   67 |  12 |   MISO.0 | ALT4 | 0 | 21 || 22 | 0 | OFF  | RTS.3    | 13  | 121  |
 |   64 |  14 |   SCLK.0 | ALT4 | 0 | 23 || 24 | 0 | ALT4 | CE.0     | 15  | 69   |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PH03     | 16  | 227  |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+  OPi H6  +---+------+----------+-----+------+
```

## Allwinner H616

### Orange Pi Zero2/Zero2 LTS/Zero2 B

```
 +------+-----+----------+------+---+  Zero 2  +---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |  229 |   0 |    SDA.3 |  OFF | 0 |  3 || 4  |   |      | 5V       |     |      |
 |  228 |   1 |    SCL.3 |  OFF | 0 |  5 || 6  |   |      | GND      |     |      |
 |   73 |   2 |      PC9 |  OFF | 0 |  7 || 8  | 0 | ALT2 | TXD.5    | 3   | 226  |
 |      |     |      GND |      |   |  9 || 10 | 0 | ALT2 | RXD.5    | 4   | 227  |
 |   70 |   5 |      PC6 | ALT5 | 0 | 11 || 12 | 0 | OFF  | PC11     | 6   | 75   |
 |   69 |   7 |      PC5 | ALT5 | 0 | 13 || 14 |   |      | GND      |     |      |
 |   72 |   8 |      PC8 |  OFF | 0 | 15 || 16 | 0 | OFF  | PC15     | 9   | 79   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | OFF  | PC14     | 10  | 78   |
 |  231 |  11 |   MOSI.1 | ALT4 | 0 | 19 || 20 |   |      | GND      |     |      |
 |  232 |  12 |   MISO.1 | ALT4 | 0 | 21 || 22 | 0 | OFF  | PC7      | 13  | 71   |
 |  230 |  14 |   SCLK.1 | ALT4 | 0 | 23 || 24 | 0 | ALT4 | CE.1     | 15  | 233  |
 |      |     |      GND |      |   | 25 || 26 | 0 | OFF  | PC10     | 16  | 74   |
 |   65 |  17 |      PC1 |  OFF | 0 | 27 || 28 |   |      |          |     |      |
 |  272 |  18 |     PI16 |  OFF | 0 | 29 || 30 |   |      |          |     |      |
 |  262 |  19 |      PI6 |  OFF | 0 | 31 || 32 |   |      |          |     |      |
 |  234 |  20 |     PH10 | ALT3 | 0 | 33 || 34 |   |      |          |     |      |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+  Zero 2  +---+------+----------+-----+------+
```

## RockChip RK3399 

### Orange Pi RK3399

```
 +------+-----+----------+------+---+OPi RK3399+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   43 |   0 |    SDA.0 | ALT2 | 1 |  3 || 4  |   |      | 5V       |     |      |
 |   44 |   1 |    SCL.0 | ALT2 | 1 |  5 || 6  |   |      | GND      |     |      |
 |   64 |   2 |    GPIO4 | ALT3 | 0 |  7 || 8  | 0 | ALT2 | Tx       | 3   | 148  |
 |      |     |      GND |      |   |  9 || 10 | 1 | ALT2 | Rx       | 4   | 147  |
 |   80 |   5 |   GPIO17 | ALT2 | 0 | 11 || 12 | 0 | ALT3 | GPIO18   | 6   | 65   |
 |   81 |   7 |   GPIO27 | ALT2 | 0 | 13 || 14 |   |      | GND      |     |      |
 |   82 |   8 |   GPIO22 | ALT2 | 0 | 15 || 16 | 0 | IN   | GPIO23   | 9   | 66   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | IN   | GPIO24   | 10  | 67   |
 |   39 |  11 |     MOSI | ALT2 | 1 | 19 || 20 |   |      | GND      |     |      |
 |   40 |  12 |     MISO | ALT2 | 1 | 21 || 22 | 0 | ALT2 | GPIO25   | 13  | 83   |
 |   41 |  14 |     SCLK | ALT3 | 1 | 23 || 24 | 1 | ALT3 | CS0      | 15  | 42   |
 |      |     |      GND |      |   | 25 || 26 | 0 | ALT2 | CS1      | 16  | 133  |
 |  154 |  17 |     DNP1 |   IN | 0 | 27 || 28 | 1 | IN   | DNP2     | 18  | 50   |
 |   68 |  19 |    GPIO5 |  OUT | 1 | 29 || 30 |   |      | GND      |     |      |
 |   69 |  20 |    GPIO6 |  OUT | 1 | 31 || 32 | 1 | OUT  | GPIO12   | 21  | 76   |
 |   70 |  22 |   GPIO13 |  OUT | 1 | 33 || 34 |   |      | GND      |     |      |
 |   71 |  23 |   GPIO19 |  OUT | 1 | 35 || 36 | 1 | OUT  | GPIO16   | 24  | 73   |
 |   72 |  25 |   GPIO26 |  OUT | 1 | 37 || 38 | 0 | IN   | GPIO20   | 26  | 74   |
 |      |     |      GND |      |   | 39 || 40 | 0 | ALT4 | GPIO21   | 27  | 75   |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+OPi RK3399+---+------+----------+-----+------+
 ```
 
 ### Orange Pi 4/4B/4 LTS

 ```
 +------+-----+----------+------+---+OrangePi 4+---+---+--+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 |      |     |     3.3V |      |   |  1 || 2  |   |      | 5V       |     |      |
 |   64 |   0 | I2C2_SDA | ALT3 | 0 |  3 || 4  |   |      | 5V       |     |      |
 |   65 |   1 | I2C2_SCL | ALT3 | 0 |  5 || 6  |   |      | GND      |     |      |
 |  150 |   2 |     PWM1 |   IN | 0 |  7 || 8  | 1 | ALT2 | I2C3_SCL | 3   | 145  |
 |      |     |      GND |      |   |  9 || 10 | 1 | ALT2 | I2C3_SDA | 4   | 144  |
 |   33 |   5 | GPIO1_A1 |   IN | 0 | 11 || 12 | 1 | IN   | GPIO1_C2 | 6   | 50   |
 |   35 |   7 | GPIO1_A3 |  OUT | 0 | 13 || 14 |   |      | GND      |     |      |
 |   92 |   8 | GPIO2_D4 |  OUT | 1 | 15 || 16 | 0 | IN   | GPIO1_C6 | 9   | 54   |
 |      |     |     3.3V |      |   | 17 || 18 | 0 | IN   | GPIO1_C7 | 10  | 55   |
 |   40 |  11 | SPI1_TXD | ALT2 | 1 | 19 || 20 |   |      | GND      |     |      |
 |   39 |  12 | SPI1_RXD | ALT2 | 1 | 21 || 22 | 0 | IN   | GPIO1_D0 | 13  | 56   |
 |   41 |  14 | SPI1_CLK | ALT3 | 1 | 23 || 24 | 1 | ALT3 | SPI1_CS  | 15  | 42   |
 |      |     |      GND |      |   | 25 || 26 | 0 | IN   | GPIO4_C5 | 16  | 149  |
 |   64 |  17 | I2C2_SDA | ALT3 | 0 | 27 || 28 | 0 | ALT3 | I2C2_SCL | 18  | 65   |
 |      |     |  I2S0_RX |      |   | 29 || 30 |   |      | GND      |     |      |
 |      |     |  I2S0_TX |      |   | 31 || 32 |   |      | I2S_CLK  |     |      |
 |      |     | I2S0_SCK |      |   | 33 || 34 |   |      | GND      |     |      |
 |      |     | I2S0_SI0 |      |   | 35 || 36 |   |      | I2S0_SO0 |     |      |
 |      |     | I2S0_SI1 |      |   | 37 || 38 |   |      | I2S0_SI2 |     |      |
 |      |     |      GND |      |   | 39 || 40 |   |      | I2S0_SI3 |     |      |
 +------+-----+----------+------+---+----++----+---+------+----------+-----+------+
 | GPIO | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | GPIO |
 +------+-----+----------+------+---+OrangePi 4+---+---+--+----------+-----+------+
```

## COMANDOS GPIO (Página Oficial http://wiringpi.com/the-gpio-utility/)

Standard input and output commands
gpio mode <pin> in/out/pwm/clock/up/down/tri
This sets the mode of a pin to be input, output, pwm or clock mode, and additionally can set the internal pull-up/down resistors to pull-up, pull-down or none.

gpio write <pin> 0/1
This sets an output pin to high (1) or low (0)

gpio pwm <pin> <value>
Set the pin to a PWM value (0-1023 is supported)

gpio read <pin>
Reads and prints the logic value of the given pin. It will print 0 (low) or 1 (high).

gpio awrite <pin> <value>
This performs an analog read from the given pin. The Pi has no on-board analog hardware so you need to specify an external module using the -x flag.

gpio aread <pin>
This read the analog value on the given pin. The has no on-board analog hardware so you need to specify an external module using the -x flag.

gpio readall
This reads all the normally accessible pins and prints a table of their numbers (wiringPi, BCM_GPIO and physical pin numbers), so makes for a handy cross-reference chart), along with their modes and current values. This command will detect the version/model of your Pi and printout the pin diagram appropriate to your Pi.

gpio allreadall
This reads all the pins on your Raspberry Pi. It’s essentially the same format as used on the Compute Module.

gpio wfi <pin> rising/falling/both
This causes GPIO to perform a non-busy wait on a single GPIO pin until it changes state to that indicated.

Kernel module Load Commands
Note that these command will not work if you have enabled the device-tree interface. A warning will be printed if-so.

gpio load spi [buffer size in KB]
This loads the SPI kernel modules and optionally sets the internal buffer to the given size in KB (multiples of 1024). The default is 4KB and is usually more than enough for most application which only exchange a byte or 2 at a time over the SPI bus.

The /dev/spi* entries are set to be owned by the person using the gpio program, so there is no need to run subsequent programs as root (unless they use other wiringPi functions)

gpio load i2c [baud rate in Kb/sec]
This loads the I2C kernel modules and optionally sets the baud rate to the given speed in Kb/sec (multiples of 1000). The default is 100Kb/sec.

The /dev/I2c* entries are set to be owned by the person using the gpio program, so there is no need to run subsequent programs as root (unless they use other wiringPi functions)

I2C Detection
gpio i2cdetect
This runs the i2cdetect command, but passes in the correct parameters for the I2C bus for the Pi’s hardware revision. ie. it runs i2cdetect -y 0 on a Rev. 1 Pi, and i2cdetect -y 1 on a Rev. 2 Pi. (You can shorten i2cdetect to i2cd)

/sys/class/gpio mode commands
gpio export <pin> in/out
This exports the given pin (BCM-GPIO pin number) as an input or output and makes it available for a user program running as the same user to use.

gpio unexport <pin>
Removes the export of the given pin.

gpio unexportall
Removes all /sys/class/gpio exports.

gpio exports
This prints a list of all gpio pins which have been exported via the /sys/class/gpio interface and their modes.

gpio edge <pin> rising/falling/both/none
This enables the given pin for edge interrupt triggering on the rising, falling or both edges. (Or none which disables it)

Note: The pin numbers in the sys mode are always BCM-GPIO pin numbers.

Examples
gpio mode 0 out
gpio write 0 1
The above uses the wiringPi pin numbers to set pin 0 as an output and then sets the pin to a logic 1.

gpio -g mode 17 out
gpio -g write 17 1
This uses the BCM_GPIO pin numbering scheme and performs the same operation as above.

gpio -1 mode 11 out
gpio -1 write 11 1
This uses the physical P1 pin numbering scheme and performs the same operation as above.

Internal pull up/down resistors
The GPIO lines have internal pull up or pull-down resistors which can be controlled via software when a pin is in input mode. There is no-way to read the status of these resistors.

gpio mode 0 up
gpio mode 0 down
gpio mode 0 tri
These set the resistors to pull-up, pull-down and none respectively on wiringPi pin 0
