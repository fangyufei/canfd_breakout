# canfd_breakout
 
Small footprint can-fd breakout board.
Arduino libray acan2517fd works well.

https://github.com/pierremolinaro/acan2517FD

IO Voltage Vio can be set via 0Ohm Resistor R2=>3V3 or R3=>5V.
Even when Vio is set to 3V3, the board (the transceiver) needs 5V supply for proper CAN sending.

The 40MHz crystal can be replaced by a 20MHz or 4MHz crystal. However this affects CAN timing parameters in SW.

PCB:
![image](https://github.com/fangyufei/canfd_breakout/assets/40605053/2766087c-93bb-45a6-8511-05763cf39c43)

![image](https://github.com/fangyufei/canfd_breakout/assets/40605053/6e953370-aff8-4972-b4e0-97e55a291c95)

![image](https://github.com/fangyufei/canfd_breakout/assets/40605053/c0f4731d-3f10-4301-a8a6-ac09521a7714)
