# MoErgo Glove80 Custom Configuration for ZMK

![Glove80](glove80.jpg)

This is the ZMK configuration of my MoErgo Glove80 wireless split contoured keyboard.
Most of the configuration is inside the [glove80.keymap](config/glove80.keymap) file.

## Layers

The keymaps can be shown using the `bin/keys` command, which greps the [glove80.keymap](config/glove80.keymap) to get the latest layouts.

```text

   DEFAULT
  F|F1 |F2 |F3 |F4 |F5 | __ | __ | __ | __ | | __ | __ | __ | __ |F6 |F7 |F8 |F9 |F10|
  N|F11| 1 | 2 | 3 | 4 | 5  | __ | __ | __ | | __ | __ | __ |  6 | 7 | 8 | 9 | 0 |F12|
   |   | Q | W | E | R | T  | __ | __ | __ | | __ | __ | __ |  Y | U | I | O | P |   |
  >|   | A | S | D | F | G  | __ | __ | __ | | __ | __ | __ |  H | J | K | L | - |   |
   |   | Z | X | C | V | B  | Esc|Ctrl|LAlt| |GERM|Ctrl|Ret |  N | M | , | . | / |   |
  L|✨ |Hom|End|Lft|Rgt| __ |Bksp|Shft|SYMB| |SYMB|Shft|Spce| __ |Dwn|Up |PDn|PUp|Sys|
   Spce: &mod_space_alt_tab


   SYMBOLS
  F|   |   |   |   |   | __ | __ | __ | __ | | __ | __ | __ | __ |   |   |   |   |   |
  N|   | ! |   |   |   | %  | __ | __ | __ | | __ | __ | __ |  ^ |   |   |   | ø |   |
   |   | ? | = | { | } | '  | __ | __ | __ | | __ | __ | __ |  # | ~ | & | + | ^ |   |
  >|   | @ | * | ( | ) | "  | __ | __ | __ | | __ | __ | __ |  < | - |Pip| > | - |   |
   |   | € | $ | [ | ] | `  |    |    |NUMB| |    |    |    |  \ | _ | , | . | / |   |
  L|✨ |   |   |   |   | __ |    |    |    | |    |    |    | __ |   |   |   |   |   |


   GERMAN
  F|   |   |   |   |   | __ | __ | __ | __ | | __ | __ | __ | __ |   |   |   |   |   |
  N|   |   |   |   |   |    | __ | __ | __ | | __ | __ | __ |    |   |   |   |   |   |
   |   |   |   |   |   |    | __ | __ | __ | | __ | __ | __ |    | Ü |   | Ö |   |   |
  >|   | Ä | ß |   |   |    | __ | __ | __ | | __ | __ | __ |    |   |   |   |   |   |
   |   |   |   |   |   |    |    |    |    | |    |    |    |    |   |   |   |   |   |
  L|✨ |   |   |   |   | __ |    |    |    | |    |    |    | __ |   |   |   |   |   |


   NUMBLOCK
  F|   |   |   |   |   | __ | __ | __ | __ | | __ | __ | __ | __ |   |   |   |   |   |
  N|   |   |   |   |   |    | __ | __ | __ | | __ | __ | __ |  ^ |   | * |   |   |   |
   |   |   |   |   |   |    | __ | __ | __ | | __ | __ | __ |    | 7 | 8 | 9 | + |   |
  >|   |   |   |   |   |    | __ | __ | __ | | __ | __ | __ |    | 4 | 5 | 6 | - |   |
   |   |   |   |   |   |    |    |    |    | |    |    |    |    | 1 | 2 | 3 |Ret|   |
  L|✨ |   |   |   |   | __ |    |    |SYMB| |SYMB|    |    | __ | 0 | 0 | . |Ret|   |


   MAGIC
  F|BtC|   |   |   |   | __ | __ | __ | __ | | __ | __ | __ | __ |   |   |   |   |BtC|
  N|   |   |   |   |   |    | __ | __ | __ | | __ | __ | __ |    |   |   |   |   |   |
   |   |RGB|RGB|RGB|RGB|RGB | __ | __ | __ | | __ | __ | __ |    |   |   |   |   |   |
  >|BLd|Spd|Sat|Hue|Brd|Efct| __ | __ | __ | | __ | __ | __ |    |   |   |   |   |BLd|
   |Rst|   |   |   |   |    | BT2| BT3|    | |    |    |    |    |   |   |   |   |Rst|
  L|✨ |   |   |   |   | __ | BT0| BT1| USB| |    |    |    | __ |   |   |   |   |   |


   RGB
  F|   |   |Cap|Num|Scr| __ | __ | __ | __ | | __ | __ | __ | __ |   |   |   |   |   |
  N|DEF|SYM|GER|NUM|MAG|    | __ | __ | __ | | __ | __ | __ |    |   |   |   |   |   |
   |UbL|UbL|UbL|UbL|UbL|UbL | __ | __ | __ | | __ | __ | __ |    |   |   |   |   |   |
  >|UbR|UbR|UbR|UbR|UbR|UbR | __ | __ | __ | | __ | __ | __ |    |   |   |   |   |   |
   |   |   |   |   |   |    | BT2| BT3|    | |    |    |    |    |   |   |   |   |   |
  L|✨ |   |   |   |   | __ | BT0| BT1| USB| |    |    |    | __ |   |   |   |   |   |

```

## Resources

For your own configuration, you might want to create your own configuration based on
the [MoErgo Glove80 template repo](https://github.com/moergo-sc/glove80-zmk-config).

## Firmware Files

1. Download the glove80.uf2 from the latest run in [Github Actions](https://github.com/f0i/glove80/actions)
2. Put the Glove80 in bootloader mode (Magic + outer home row key)
3. Copy over the glove80.uf2 file and wait for it to reboot.

