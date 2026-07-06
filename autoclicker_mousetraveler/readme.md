patch for some anti-vm mouse / clicks checks

affected files:
```
hw/input/hid.c
include/hw/input/hid.h
hw/usb/dev-hid.c
```

run with command
```
-device usb-mouse,mouse_traveler=on,autoclicker=on
```