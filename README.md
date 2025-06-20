# NDSL Clicky Buttons

Forked from [`facelesstech/ds_lite_clicky_buttons`][0], his original blog post can be found [here][1].

![alt text](https://github.com/facelesstech/ds_lite_clicky_buttons/blob/main/PXL_20220701_142012562.jpg?raw=true)

### Motherboard reference

| Test Point | Function             |
|------------|----------------------|
| P00        | A                    |
| P01        | B                    |
| P02        | SELECT               |
| P03        | START                |
| P04        | RIGHT                |
| P05        | LEFT                 |
| P06        | UP                   |
| P07        | DOWN                 |
| P08        | L_TRIGGER            |
| P09        | R_TRIGGER            |
| R00        | X                    |
| R01        | Y                    |
| LEDC2      | GND                  |
| SPL0       | L_SPEAKER+           |
| LEDA2      | Top screen backlight |

To bypass the top screen, a 330-Ohm resistor should be bridged to LEDA2 and LEDC2.

[0]: https://github.com/facelesstech/ds_lite_clicky_buttons
[1]: https://facelesstech.wordpress.com/2022/07/23/ds-lite-clicky-buttons/
