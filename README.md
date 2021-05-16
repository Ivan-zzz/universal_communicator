# universal_communicator
Communicator (wifi/bluetooth+radiomodule+communication with smartphone and PC).

Hi there. I want to create communicator device with following functionality:
1) Communication between 2 similar devices (sms / voice / data-files transferring)
- by integrated radiomodules (wifi esp32-now)
- by external radiomodules (nrf24l01+)
- by external radiomodules (lora E220)
2) Interaction with smartphones (wifi / bluetooth / USB)
- as external radiomodem (add-on to any smartphone) with full smartphone functionality
- as main device which uses smartphone for input/indication
3) Compass + GPS receiver and tracker 
- get GPS coordinates and heading  and transfer to 2nd devuce or to a group
- estimate range between 2 points (to the other device or inputed coordinates, or base choosen coordinates). 


Basement - ESP32 modules (like devkit)
input - from nextion display, or any other touchscreen display. Optionally - no input and using smartphone or PC for input/indication (for add-on type of device).
long range short messaging - Lora
Mid-range voice talking - NRF24 (not necessary if integrated wifi with amplifier and external antenna reach the same range).
low-range fast communiction - integrated wifi/bluetooth (but not necessary if NRF is working fine). 

If sbdy interested and wants to help in development of such device - feel free to contact me. 
Thx.
