---
title: "Tools"
---

Both official and unofficial tools that can make working with QMK easier.

---

### QMK Configurator

https://config.qmk.fm

Awesome tool for anybody who does not need advanced funtionality, just an easy way to work on keymaps.

---

### kbfirmware.com -> mainline QMK converter

https://noroadsleft.github.io/kbf_qmk_converter

Behind the scenes, kbfirmware.com uses an ancient fork of QMK (3+ years old, afaik).  
Tries to bring the code generated by kbfirmware.com up to standards.  
It's a great starting point to add support for boards that has kbfirmware json but not supported by mainline QMK.

---

### VID/PID usage info

https://yanfali.github.io/qmk_usb_usage

Vendor and product IDs become a topic of conversation with VIA, since it uses these two values to indentify a board.  
Pulls the usage data from the QMK API and allows filtering.  
Useful for those thinking about adding VIA support for their boards.

---

### Helix font editor

https://helixfonteditor.netlify.app

Allows you to upload a `glcdfont.c` file, edit it and save it back to C file. Useful for OLED-lovers.

---

### Logo editor

https://joric.github.io/qle

Another useful tool for users of OLED screens.

---

### Combo generator

https://codepen.io/mvaneijgen/full/LYEVQXp

Handy tool for generating [Combos](https://docs.qmk.fm/#/feature_combo?id=combos).
