## How to download wiringOP
```
# apt-get update
# apt-get install -y git
# git clone https://github.com/orangepi-xunlong/wiringOP.git
How to build wiringOP
# cd wiringOP
# ./build clean
# ./build 
```

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

## USO
Na linha de comando do Linux:


```
# gpio -v
```
Isso imprime a versão.


```
# gpio -g …
```
O sinalizador -g opcional faz com que os números dos pinos sejam interpretados como números de pinos BCM_GPIO em vez de números de pinos padrão do wirePi.


```
# gpio -1 …
```
O sinalizador opcional -1 faz com que os números dos pinos sejam interpretados como números de pinos de hardware - isso funciona apenas para o conector P1.


```
# gpio -p …
```
O sinalizador -p opcional faz com que o programa gpio assuma que há uma placa PiFace instalada no Rasberry Pi e os comandos subsequentes são interpretados como pinos no PiFace. Observação: os pinos no PiFace são de 200 a 207 para leitura e gravação, com os pinos 208 a 215 lendo o estado do registro de latch de saída (ou seja, você pode ler o estado dos pinos de saída)


```
#gpio -x …
```
O sinalizador -x opcional faz com que o programa gpio inicialize um módulo de expansão adicional. Os módulos de expansão são definidos com seu nome (por exemplo, mcp23s17) e um conjunto de parâmetros separados por dois pontos. O primeiro parâmetro é sempre o número do pino base para este módulo de expansão. Consulte a documentação de cada tipo de módulo para determinar os valores e funções de parâmetros adicionais.


## Comandos padrão de entrada e saída


```
# gpio mode <pin> in/out/pwm/clock/up/down/tri
```
Isso define o modo de um pino para entrada, saída, pwm ou modo de relógio e, adicionalmente, pode definir os resistores pull-up/down internos para pull-up, pull-down ou nenhum.


```
# gpio write <pin> 0/1
```
Isso define um pino de saída para alto (1) ou baixo (0)


```
# gpio pwm <pin> <value>
```
Defina o pino para um valor PWM (0-1023 é suportado)


```
# gpio read <pin>
```
Lê e imprime o valor lógico do pino fornecido. Ele imprimirá 0 (baixo) ou 1 (alto).


```
# gpio awrite <pin> <value>
```
Isso executa uma leitura analógica do pino fornecido. O Pi não possui hardware analógico integrado, portanto, você precisa especificar um módulo externo usando o sinalizador -x.


```
# gpio aread <pin>
```
Isso lê o valor analógico no pino fornecido. O não possui hardware analógico on-board, então você precisa especificar um módulo externo usando o sinalizador -x.


```
# gpio readall
```
Isso lê todos os pinos normalmente acessíveis e imprime uma tabela de seus números (wiringPi, BCM_GPIO e números de pinos físicos), criando um gráfico de referência cruzada útil), juntamente com seus modos e valores atuais. Este comando detectará a versão/modelo do seu Pi e imprimirá o diagrama de pinos apropriado para o seu Pi.


```
# gpio allreadall
```
Isso lê todos os pinos do seu Raspberry Pi. É essencialmente o mesmo formato usado no Compute Module.


```
# gpio wfi <pin> rising/falling/both
```
Isso faz com que o GPIO execute uma espera não ocupada em um único pino GPIO até que ele mude de estado para o indicado.


# Comandos de carregamento do módulo do kernel
Observe que esses comandos não funcionarão se você tiver habilitado a interface device-tree. Um aviso será impresso se assim for.


```
# gpio load spi [buffer size in KB]
```
Isso carrega os módulos do kernel SPI e, opcionalmente, define o buffer interno para o tamanho especificado em KB (múltiplos de 1024). O padrão é 4 KB e geralmente é mais do que suficiente para a maioria dos aplicativos que trocam apenas um byte ou 2 por vez no barramento SPI.


As entradas /dev/spi* são definidas para pertencer à pessoa que usa o programa gpio, portanto, não há necessidade de executar programas subsequentes como root (a menos que eles usem outras funções do wirePi)


```
# gpio load i2c [baud rate in Kb/sec]
```
Isso carrega os módulos do kernel I2C e, opcionalmente, define a taxa de transmissão para a velocidade fornecida em Kb/s (múltiplos de 1000). O padrão é 100Kb/seg.


As entradas /dev/I2c* são definidas para pertencer à pessoa que usa o programa gpio, portanto, não há necessidade de executar programas subsequentes como root (a menos que eles usem outras funções do wirePi)


## Detecção I2C


```
# gpio i2cdetect
```
Isso executa o comando i2cdetect, mas passa os parâmetros corretos para o barramento I2C para a revisão de hardware do Pi. ou seja ele executa i2cdetect -y 0 em um Rev. 1 Pi e i2cdetect -y 1 em um Rev. 2 Pi. (Você pode encurtar i2cdetect para i2cd)


## comandos /sys/class/gpio mode
```
# gpio export <pin> in/out
```
Isso exporta o pino fornecido (número do pino BCM-GPIO) como uma entrada ou saída e o torna disponível para um programa de usuário em execução como o mesmo usuário.


```
# gpio unexport <pin>
```
Remove a exportação do pino fornecido.


```
# gpio unexportall
```
Remove todas as exportações /sys/class/gpio.


```
# gpio exports
```
Isso imprime uma lista de todos os pinos gpio que foram exportados por meio da interface /sys/class/gpio e seus modos.


```
# gpio edge <pin> rising/falling/both/none
```
Isso permite que o pino fornecido para interrupção de borda seja acionado na borda ascendente, descendente ou em ambas as bordas. (Ou nenhum que o desabilita)


Nota: Os números dos pinos no modo sys são sempre números dos pinos BCM-GPIO.


## Exemplos
```
# gpio mode 0 out
# gpio write 0 1
```
O acima usa os números dos pinos do wirePi para definir o pino 0 como uma saída e, em seguida, define o pino para uma lógica 1.


```
# gpio -g mode 17 out
# gpio -g write 17 1
```
Isso usa o esquema de numeração de pinos BCM_GPIO e executa a mesma operação acima.


```
# gpio -1 mode 11 out
# gpio -1 write 11 1
```
Isso usa o esquema de numeração de pino P1 físico e executa a mesma operação acima.


## Resistores pull up/down internos
As linhas GPIO possuem resistores pull-up ou pull-down internos que podem ser controlados via software quando um pino está no modo de entrada. Não há como ler o status desses resistores.


```
# gpio mode 0 up
# gpio mode 0 down
# gpio mode 0 tri
```
Estes definem os resistores para pull-up, pull-down e nenhum respectivamente na fiaçãoPi pino 0
