# Bento Macropad


![Bento](https://i.imgur.com/DvuAeQq.jpg)


The Bento Macropad is a 5-key macropad with rotary encoder designed by Dwin17 (Discord: **Dwin#3766**, Reddit: **nguyedt**) with PCB designed by coarse (keyboard.coarse.tech). 

**Key features include:**
- Powered by QMK Firmware
- EC11 Rotary Encoder
- RGB Underglow
- Files for 3d printing of the box remodeled by (flpcnc)
________________________________________________________________________________________________________________________________________________________________

**FAQ**

* Can you post a compiled firmware?
  - yes, I'm using this one from user c0qu1 with 4 layers - https://github.com/c0qu1/bento/releases
* Is this project original from flpcnc?
  - No. You can find the forked project here: https://github.com/Dwin17/bento
  - I would also like to credit @mttpsck on GitHub for the 4 layer content
* Is VIA support working perfectly?
  - Almost, rotary encoder is not supported by VIA. The firmware provides support for the rotary encoder which works at the same time as supporting VIA on the 4 contiguous keys and the integrated rotary encoder button. The 5th key is used to cycle through all layers and this is not supported by VIA as it is a custom function in QMK. The layer switch switch has been removed from the VIA layout to prevent accidental modification of the layout.
* Because it does not work?
  - See the troubleshooting guide in the original project, see above.
* VIA does not recognize my Bento, why?
  - You must import the keymaps/via/bento.json file into VIA every time you open VIA, until Bento Macropad is officially added to VIA this will be required.
* How do I acquire the refurbished 3D printing files?
  - files for 3d printing redesigned by flpcnc with an amazing advantage: you don't need to use supports during printing! With the modifications that were made without support, ensuring that the printing process is easy and accessible even for novice 3D printing users.
* What is the cost of refurbished 3d files?
  - It took hours of work to arrive at this 3D modification, which is why the remodeled file will be available for a symbolic value  of 3 dollars, just to cover energy costs and invest in new improvements, software and the development of new projects.
* link to download the refurbished 3d file:
  - https://cults3d.com/en/3d-model/gadget/another-bento-macropad  
________________________________________________________________________________________________________________________________________________________________

**Flashing a new layout**

*Please do not use QMK Configurator to create firmware for the Bento. The Bento located on QMK Configurator is only for the handwired version and will not work*

Make example for this keyboard (after setting up your build environment):

    make bento:default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with the [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).


[Video Guide for creating macropad firmware manually](https://www.youtube.com/watch?v=-HLV6mUxNnU&list=PLYEUsdlqPD2a3kzQgnF98Prj-4IzZJGYG)

[Video Guide to using QMK Toolbox to flash your macropad](https://www.youtube.com/watch?v=VR53Wo9Z960&t=1s)


**To put your Bento into bootloader mode, please turn it over and press the reset button located through the cutout on the bottom plate.**

________________________________________________________________________________________________________________________________________________________________

**NOTE:** If you have received a built Bento Macropad from me, it will be flashed with this layout by default: 

![Bento](https://i.imgur.com/8bssMvj.jpg)
