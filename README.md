# Mega2560-SPI-Driver
A simple implementation of a Master SPI class in C++ for the Mega2560. This is a part of a semester project on the 2. semester of the Bachelor of Engineering in Software Technology at Aarhus University. The implementation is pretty bare bones in its current state. It should work fine for other AVR MCU's with some slight changes to the code. You would need to change the MISO, MOSI, SS and SCK pins to the pins of your AVR MCU. This would have to be done in the InitSPI(), SS_High() and SS_low() methods.
