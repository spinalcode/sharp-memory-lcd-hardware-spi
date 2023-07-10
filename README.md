# sharp-memory-lcd-hardware-spi
Using hardware SPI on sharm memory LCD

As the adafruit example only uses software SPI, it gets really poor FPS.
This example (very basic) uses hardware SPI at 8mhz. This gives 100fps on the 144x168 screen.
The demo I have, switches between 3 images, using persistance of vision to give 4 grey colours.
