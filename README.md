# Display PCB for the pedalboard-hw

Features:

- 8 LED RGB rings
- Each of the 12 LEDs on a ring can get an individual color.
- The led rings are cascaded and addressed via a single serial line.
- Connector: Stemma conform 3 pin JST-PH
- 2 additional single LEDs
- 2 ports for 4 wire OLED displays with 4 pin Stemma connectors

## Generated Hardware Documentation

Interactive [KiCanvas](https://kicanvas.org/?github=https%3A%2F%2Fgithub.com%2Fpedalboard%2Fpedalboard-display%2Ftree%2Fmain) viewer.

Downloadable [Assets](https://pedalboard.github.io/pedalboard-display-site/latest) are generated with [KiBot](https://github.com/INTI-CMNB/KiBot)

## Fabrication

- [Generated iBOM](https://pedalboard.github.io/pedalboard-display-site/latest/Assembly/pedalboard-display-ibom.html)
- [Digi-Key shared list](https://www.digikey.ch/de/mylists/list/I3LZUQ0FSV)

## 3D Views

![Top View](https://pedalboard.github.io/pedalboard-display-site/latest/3D/pedalboard-display-3D_blender_top.png)
![Bottom View](https://pedalboard.github.io/pedalboard-display-site/latest/3D/pedalboard-display-3D_blender_bottom.png)
![30 deg View](https://pedalboard.github.io/pedalboard-display-site/latest/3D/pedalboard-display-3D_blender_30deg.png)

## Additional mechanical components

- Foot switch actuator: [Data Sheet](https://www.cliffuk.co.uk/products/switches/FC7125.pdf) [3D Model](https://github.com/pedalboard/pedalboard-case/blob/main/generated/actuator.stl)
- Washer: [3D Model](https://github.com/pedalboard/pedalboard-case/blob/main/generated/led-ring-washer.stl)
- Display: <https://www.aliexpress.com/item/1005005253671396.html>

## How to release

The release procedure is the same as for [pedalboard-hw](https://github.com/pedalboard/pedalboard-hw/blob/main/doc/release-procedure.md)
