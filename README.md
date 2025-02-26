# Pentangeli ZMK configuration

Configuration for Pentangeli, a 38 key hand-wired keyboard with integrated trackball.


### TODO

- [x] Remove encoder support
- [x] Adapt pinout for cols and rows
- [x] Add [sensor driver](https://github.com/inorichi/zmk-pmw3610-driver) and [configure pointing device](https://zmk.dev/docs/development/hardware-integration/pointing)
- [ ] Adjust key matrix for 38 keys
- [ ] Add nice!view adapter and enable
- [ ] Update keymap to the same as QMK, but with BT keys on macro layer
- [ ] Potentially add build guide

### References
- [New shield ZMK documentation](https://zmk.dev/docs/development/hardware-integration/new-shield)
- [Waterfowl shield configuration used as starting point](https://github.com/zmkfirmware/zmk/tree/main/app/boards/shields/waterfowl)
- [Frankie Pentangeli](https://m.imdb.com/title/tt0071562/characters/nm0311155/)

- [pmw3610 Pinout reddit](https://www.reddit.com/r/ErgoMechKeyboards/comments/1h0zy8n/help_which_nicenane_pins_to_connect_to_this/#lightbox)
- [pmw3610-pcb](https://github.com/siderakb/pmw3610-pcb)
- [zmk-pmw3610-driver](https://github.com/inorichi/zmk-pmw3610-driver)


Default Nice!View pinout:
```
CS = D1 / P0.06
SCL = D2 / 0.17
MOSI = D3 / P0.20
```

Custom pinout:
```
CS   = D14 / P1.11
SCL  = D16 / P0.10
MOSI = D10 / P0.09

```
