~~qmk clean~~
~~qmk compile -kb planck/rev1 -km jama211~~
~~qmk flash -kb planck/rev1 -km jama211~~

NO! Those are wrong, because it's actually a rev4 board lol... 

jama211_v2 fixes this and is based on rev4 default (but includes the power change for iOS in config.h), so set up your defaults and just do:

```
qmk compile
```

Then just use the QMK Toolbox to flash it... hold the top left button while plugging it in, use a toothpick, or press raise + lower + Q to put it indo DFU mode. 

jama211_v3 is based on rev4, but has my additional layout changes. 