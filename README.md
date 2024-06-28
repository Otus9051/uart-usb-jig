# MicroUSB to TTL to USB converter
## Should work with almost any Samsung device

- Connectors:
    - Micro USB B Male
    - USB A 2.0 Female
 
- Utitlizes CP2102N as the Serial to USB convertor
- ID pin of Micro USB B Male is connected to 619K Ohm Resistor
- 619K Ohm Resistance triggers Samsung MUIC to switch to USB UART mode
![Samsung Universal MUIC Code Comment Block](https://github.com/Otus9051/uart-usb-jig/assets/58171861/d3e262b2-5ee0-47e3-91b6-433b86e7710e)
- LCSC Part Numbers included in Bill of Materials
- Pulls 5V from USB A, Micro USB B gets 3.3V from CP2102 VDD (refer documentation)

![PCB 3D Side Profile](https://github.com/Otus9051/uart-usb-jig/assets/58171861/098ba1c8-fc52-4642-9080-8ed6f7bca2f4)
![PCB Front Render](https://github.com/Otus9051/uart-usb-jig/assets/58171861/5ab5d8c7-151f-48f3-b1c4-2809ebf39e43)
![PCB](https://github.com/Otus9051/uart-usb-jig/assets/58171861/5df61761-1cd6-4be4-a9eb-0830681d6815)
![Schematics](https://github.com/Otus9051/uart-usb-jig/assets/58171861/3d132587-0355-40c9-b519-e31df357cd11)

P.S.: This is my first try at making a PCB, please let me know any issues if you come across any
