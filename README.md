## poppy-eve

Replacement head design that can use a Pi4. Raspberry Pi 4-based head design for Poppy Torso and Humanoid. Embedding a screen more effectively than the last version.

### table of contents

* `doc` contains the documentation files on the Poppy Eva head:
  * `Eva_head_design.pdf` gives the design history of the head Eva.
  * `Eva_head_assemby_procedure.md` is the assembly guide to make the Eva head for the Poppy Torso or Humanoid.
* `hardware`
  * `STL` : contains the STL files to print the four parts that make the Eva head.
  * `BOM.md`: the bill of material.
  * The waveshare [screen](https://www.waveshare.com/product/raspberry-pi/displays/lcd-oled/4.3inch-dsi-lcd.htm) with cable and mounting hardware
* `software`: contains the instructions to customize the file `config.txt` in the `boot` partition of the SD card in order to use the DSI connector of the RPI4 to connect the display screen. A full example of `config.txt` is also given.
