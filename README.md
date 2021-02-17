# HendiControl


## Reverse engineering

### PCB Display

![IMG_0695_small.jpg](photos/IMG_0695_small.jpg)
Vorderseite *BETTER BT-350Q_DIS(V05) SH13383 15.10.22*

![IMG_0694_small.jpg](photos/IMG_0694_small.jpg)
Rückseite

Der auf der Rückseite verbaute IC trägt die Bezeichnung __SM1628__. Nach einer ersten Rechereche handelt es sich dabei um einen LED Displaycontroller.
* [Datenblatt SM1628](docu/SM1628.PDF)

### PCB Poti

![IMG_0697_small.jpg](photos/IMG_0697_small.jpg)
Vorderseite *HT-1P75*

![IMG_0699_small.jpg](photos/IMG_0699_small.jpg)
Rückseite *BETTER*

Verbaut ist ein 500K Poti

### Schaltplan

* [Schaltplan Display u. Poti](reverse_engineering/Schematic_UI.pdf)

| U [V] | P [W] |
|-------|-------|
| 0     | 3500  |
| 5     | 500   |

### Nützliche Links

* [craftbeerpi Wiki - Hendi-Induction-cooker-model-3500-M--Setup](https://github.com/Manuel83/craftbeerpi/wiki/Hendi-Induction-cooker-model-3500-M--Setup)
