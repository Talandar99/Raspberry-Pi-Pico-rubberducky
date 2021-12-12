# Pico rubber ducky (everything needed to run)

## Sources:
- https://github.com/dbisu/pico-ducky
- https://github.com/adafruit/circuitpython/releases

## Microcontroler:

![obraz](https://user-images.githubusercontent.com/32677600/145720889-7136c778-1f71-4926-827c-33dc3bc6515f.png)

### How To set up ?
- hold BOOTSEL button while connecting pico to pc 
- if you want to restore factory settings factory settings drop flash_nuke.uf2 into pico memory
- if you want to set up pico, drop adafruit-circuitpython-raspberry_pi_pico-en_US-6.3.0 into pico memory
- open adafruit_hid folder and drop keyboard.mpy into lib folder inside pico memory
- drop duckyinpython.py int pico memory and rename it to "code.py"
- open payloads folder and drop payload.dd into pico memory 
- scrip woll run instantly


