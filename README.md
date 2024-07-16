
![24-07-16-1721144087](https://github.com/user-attachments/assets/45f03e78-ad14-4455-8f45-3a8ab8315c79)

# zilpzalp
A wonky 28-key, column-staggered, unibody-split keyboard made with fantastic FOSS software: [ergogen](https://github.com/ergogen/ergogen) and [KiCad](https://www.kicad.org/).

I converted the top row and inner thumbs into breakaway tabs. This is completely untested, use at your own risk.

Some example keymaps for getting an idea of how zilpzalp may be used can be found in the [`example_keymaps` directory](https://github.com/kilipan/zilpzalp/tree/main/example_keymaps).

## BOM
- 1 pcb
- 1 Seeed XIAO compatible controller, like e.g. [Miao](https://github.com/kilipan/miao)
- 14 sot23 diodes (common cathode)
- optional (for hot swap versions only): 28 hot swap sockets  
  (choc or mx depending on pcb version)
- 28 kailh choc low profile switches
- 28 fitting keycaps (pay special attention here when building the cfx or minimal-spacing version!)

## Firmware
I personally use and recommend [ZMK firmware](https://github.com/kilipan/zmk-config-zilpzalp) which is tested and confirmed-functional for the Seeed XIAO RP2040 and the Seeed XIAO BLE controllers.  
Check out [FAK firmware](https://github.com/semickolon/fak) if you're planning to use the Miao!  
[QMK firmware](https://github.com/kilipan/qmk-config-zilpzalp) for the Seeed XIAO RP2040 is also available.

## Inspiration
- all the fantastic keyboards, knowledge, and help by [GEIST](https://github.com/GEIGEIGEIST/), [Freya](https://linktr.ee/freya_irl), [Bob](https://github.com/GroooveBob), and the wonderful Clacktales keyboard community
- the [hummingbird](https://github.com/PJE66/hummingbird) keyboard and the [rufous](https://github.com/jcmkk3/trochilidae#rufous) variation
- the [aptmak](https://github.com/apsu/aptmak) keymap

<p align="center">

![zilpzalp](https://github.com/kilipan/zilpzalp/blob/main/img/zilpzalp.png?raw=true)

</p>
