# Cornel

yet another [Crkbd](https://github.com/foostan/crkbd) clone, but with 5 rows.

---


<details>
<summary> Disclaimer </summary>

 ignore this if you're brave enough, like, if you know what Kailh Choc is, then
you are safe.

>  THIS PROJECT IS CURRENTLY WORK IN PROGRESS, NOTHING IS CLEAR, EVERY SPECIFICA-
> TION and/or DIMENSIONS and/or FEATURES and EVERYTHING MIGHT BE ABLE TO CHANGED
> WITHOUT ANY NOTICE. THIS MIGHT NOT FIT WITH YOUR LASER-ETCHED PLATE. THIS MIGHT
> DOES NOT FIT INTO YOUR $400 ALUMINUM CNC-ANODIZED CORNE CASE. YOUR CR2 BATTERY
> MIGHT BE BLOWN (SURE, I ALSO HAVE THIS RISK IN THIS CASE)
>
>  SO ANYWAY, I, HIBIYA INEMURI, DO NOT HOLD ANY TYPE OF RESPONSIBILITY IN ANY
> CASE.

</details>

## About

 According to [Crkbd](https://github.com/foostan/crkbd), the Corne keyboard is:

>  The Corne keyboard is a split keyboard with 3x6 column staggered keys and 3
> thumb keys, based on Helix. Crkbd stands for Corne Keyboard.

 Corne**l** is basically a clone of Corne keyboard, but with

* **Kailh Choc Switches** but keeping cherry pitch (19mm) for V2 keycaps.
* **Number Row**: to provide easy transition to 40% layout.
  can be removed later if no longer required. (irreversible)
* **Bluetooth MCU Support**: Cornel provides battery board (discharge only)
  that fits onto MCU cover, might be able to power [BLE Micro Pro](https://github.com/sekigon-gonnoc/BLE-Micro-Pro/), etc.
* **Low Profile**: Cornel might do any attempt to reduce thickness of keyboard.
  (TBD)

## Progress

* [ ] PCB
  * [x] Choc (revision: 1)
  * [ ] Cherry
* [ ] Plate
  * [ ] Upper (with acrylic and countersink holes)
  * [ ] Lower
* [ ] Software
  * [x] Arduino Demo (TBA)
  * [ ] QMK support
* [ ] Compability
  * [ ] Classic Pro Micro
  * [ ] [BLE Pro Micro](https://github.com/sekigon-gonnoc/BLE-Micro-Pro)
    * [ ] [LPME-IO](https://github.com/sekigon-gonnoc/LPME-IO)...?
  * [ ] [nice!nano](https://docs.nicekeyboards.com/)
  * [ ] TBA
* [ ] Problems
  * [ ] Detachability of Number row
  * [ ] removing LED Signal Skip jumper (by reordering LEDs)
* [ ] Photos

## Photos

> **WORK IN PROGRESS**

* First prototype (revision 0), with lubed 35g Burnt Orange.
  ![overall picture of revision 0](https://pbs.twimg.com/media/EvvMnn7UYAA8P6b?format=jpg&name=orig)
