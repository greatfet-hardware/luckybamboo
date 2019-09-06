# Lucky Bamboo
a quadruple 2.4 GHz ADF7242 transceiver GreatFET neighbor for monitoring Bluetooth LE 

Required KiCad dependency:

https://github.com/greatscottgadgets/gsg-kicad-lib

If you are using git, the preferred way to install gsg-kicad-lib is to use the
submodule:

```
git submodule init && git submodule update
```

## Pin usage

signal  | default pin     | alt1  | alt2
--------|---------|-------|-----
SPORT receive data 1    | J2.36 (SGPIO4)   | J2.18 (SGPIO14) |
SPORT receive data 2    | J1.07 (SGPIO7)   | J1.13 (SGPIO15) |
SPORT receive data 3     | J2.33 (SGPIO6)     | J2.29 (SGPIO7) |
SPORT receive data 4       |    J1.30 (SGPIO3)     | J1.37 (SGPIO13) |
SPORT CLK 1       |     J1.21 (SGPIO8)    |     |
SPORT CLK 2       |    J1.26 (SGPIO9)     |     |
SPORT CLK 3       |    J1.25 (SGPIO10)     |     |
SPORT CLK 4       |    J1.32 (SGPIO11)     |      |
SPI CS 1       |     J2.09    | J2.07 |
SPI CS 2       |     J1.14    | J1.16 |
SPI CS 3       |     J2.31    | J2.24 |
SPI CS 4       |     J1.34    | J1.33 |
SPI CLK       |    J1.38     |     |
SPI SI       |     J1.39    |      |
SPI SO       |    J1.40     |      |
RF switch 1       |   J2.19      |       |
RF switch 2       |    J2.23     |       |
RF switch 3       |    J2.25     |       |
RF switch 4       |    J2.27     |       |
IRQ1 1       |   2x4 header      |   J2.15    |
IRQ1 2       |    2x4 header     |   J1.18     |
IRQ1 3       |    2x4 header     |    J2.34   |
IRQ1 4       |    2x4 header     |   J1.35    |
IRQ2/TRFS 1       |   2x4 header      | J2.16      |
IRQ2/TRFS 2       |    2x4 header     |   J1.3    |
IRQ2/TRFS 3       |    2x4 header     |    J2.35   |
IRQ2/TRFS 4       |    2x4 header     |   J1.28    |
