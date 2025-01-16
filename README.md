esp32_mcp1517fd
==========

Implements a driver for the MCP2517FD SPI connected CAN module with ESP32 base hardware. 
The builtin CAN is called CAN0 (and CAN1 on dual CAN ESP32 hardware), the MCP2517FD is 
called CAN1 or CAN2 (if on dual ESP32 CAN hardware). This library is specifically meant to be used with 
the EVTV ESP32-Due board. However, with small modifications the driver found within this library 
could be used on other boards.

This library requires the can_common library. That library is a common base that 
other libraries can be built off of to allow a more universal API for CAN.

The needed can_common library is found here: https://github.com/collin80/can_common
