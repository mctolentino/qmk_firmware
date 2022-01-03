# Keymap build for Lily58 Pro RE from Next Keyboard Club (https://nextkeyboard.club/product/lily58-pro-re-mx-hotswap-keyboard/)
<img src="https://i0.wp.com/nextkeyboard.club/wp-content/uploads/2021/09/img_6204-scaled.jpeg?fit=2560%2C2560&ssl=1" width="400">

A customized lily58l keymap with rotary encoder support.

Left encoder: mouse wheel up/down, volume up/down track on RAISE layer  
Right encoder: cursor down/up, right/left on LOWER layer
Added custom logo, you may customize it by updating `lib/glcdfont_latest.c` using https://helixfonteditor.netlify.app/

* Hardware Supported: # Keymap build for Lily58 Pro RE from Next Keyboard Club (https://nextkeyboard.club/product/lily58-pro-re-mx-hotswap-keyboard/)

Compile command on QMK MSYS for this keyboard (after setting up Windows build environment):
 
    qmk compile -kb lily58 -km lily58proRE
    
or with make:

    make --jobs=1 lily58/rev1:lily58proRE

Flashing was done using QMK Toolkit.
- Load compiled hex file.
- Enable Auto-Flash option in QMK Toolkit.
- Press reset button in keyboard (you may need to do this a couple of times until it properly flashes).
- Flash both sides of the keyboard.
    
See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
