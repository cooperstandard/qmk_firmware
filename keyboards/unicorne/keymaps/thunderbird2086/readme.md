# Thunderbird2086's custom CRKBD Layout

The concept is Mac and **pinky** friendly keymap.

## Layers
- Colemak-DH: base layer. The option(⌥) and command(⌘) keys are assigned to thumb blocks as well as home position keys on each side.  Also, far end two columns are assigned to shift(⇧) and control(⌃) keys.
  ![colemak-dh](https://i.imgur.com/R7EzTTt.png)
  - Thumb keys
    | Tap         |  Double tap           |  Long tap        |
    | ---         | ---                   |  ---             |
    | Command(⌘)  | Command(⌘) + Space(␣) |                  |
    | Delete(⌦)   |                       |  Function layer  |
    | Backspace(⌫)|                       |  Function layer  |
    | Space(␣)    |                       |  Code layer      |
    | Enter(⏎)    |                       |  Code layer      |
  - Staggered keys
    | Tap         |  Double tap           |  Long tap        |
    | ---         | ---                   |  ---             |
    | TAB         | Control(⌃) + TAB      |                  |
    | a           |                       |  Control(⌃)      |
    | z           |                       |  Shift(⇧)        |
    | t           |                       |  Option(⌥)       |
    | n           |                       |  Command(⌘)      |
    | o           |                       |  Control(⌃)      |
    | '           |                       |  Control(⌃)      |
    | /           |                       |  Shift(⇧)        |
    | =           |                       |  Adjust layer    |

- QWERTY: same as Colemak-DH layer
  ![qwery](https://imgur.com/w7dH2eN.png)
  - Thumb keys : same as Colemak-DH
  - Staggered keys : almost same as Colemak-DH except
    | Tap         |  Double tap           |  Long tap        |
    | ---         | ---                   |  ---             |
    | f           |                       |  Option(⌥)       |
    | j           |                       |  Command(⌘)      |
    | ;           |                       |  Control(⌃)      |

- CODE: numbers and symbols.
  ![symbol](https://i.imgur.com/BPgPlYX.png)
  - Thumb keys
    | Tap         |  Double tap           |  Long tap        |
    | ---         | ---                   |  ---             |
    | ESC         | Caps lock             |                  |
  - Staggered keys
    | Tap         |  Double tap           |  Long tap        |
    | ---         | ---                   |  ---             |
    | `           | Command(⌘) + `        |                  |

- FUNCTION: function, meadia and navigation keys
  ![function](https://i.imgur.com/cs5haUP.png)
  - Thumb keys
    | Tap         |  Double tap           |  Long tap        |
    | ---         | ---                   |  ---             |
    | ESC         | Caps lock             |                  |

- ADJUST: RGB control, Power control, default layer setting, QMK version and reset
  ![adjust](https://i.imgur.com/T5yaCMq.png)

- SECRET: hold `ADJUST` and `FUNCTION` to activate<br>
  To enable secret macros, create `secrets.h` as shown below.
  ```c
  static const char * const secret[] = {
      "YOUR_SECRET_1",
      "YOUR_SECRET_2",
      "YOUR_SECRET_3",
      "YOUR_SECRET_4",
      "YOUR_SECRET_5"
  };
  ```
