# aai2c_slave_redirect_to_COM_port
it is based on the reference code from aardvark i2c/spi programmer.
The goal is to create a SMBUS slave device(0x10) and forward every byte received from SUT to the host computer COM 16.
It requires host to install NULL Modem software to make a virtual COM to virtual COM communcation.

