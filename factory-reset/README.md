Factory reset recipe:

Compile https://github.com/adafruit/Adafruit_Learning_System_Guides/tree/main/MagTag/MagTag_Arduino_Demos/shipping_demo for MagTag, getting `shipping_demo.ino.bin`.

```sh
uf2conv.py --family 0xbfdd4eee --base 0 shipping_demo.ino.bin --output MagTag-Factory-Reset.uf2`
```
