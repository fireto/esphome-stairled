# esphome-stairled

esphome-stairled based on ESP Home with HomeAssistant integration via MQTT or native esphome API

It controls 16 PWM outputs via PCA9685 i2c LED controller
[datasheet](https://www.nxp.com/docs/en/data-sheet/PCA9685.pdf)

Optional Temperature and barometric pressure sensor: 
[BMP180](https://www.digikey.com/htmldatasheets/production/856385/0/0/1/BMP180-Datasheet.pdf)

in order to compile and deploy this project you need to get [esphome.io](https://esphome.io)

```podman run --rm -v "${PWD}":/config --device=/dev/ttyUSB0 -it esphome/esphome:latest run ./stairLed.yml```

BOM

* [1x Olimex ESP32POE](https://www.olimex.com/Products/IoT/ESP32/ESP32-POE/open-source-hardware)
* [1x Olimex UEXT CABLE-IDC10-15cm](https://www.olimex.com/Products/Modules/Adapters/CABLE-IDC10-15cm/)
* [1x PCA9685PW 16 Channel 12-bit PWM/Servo Driver-I2C interface](https://www.aliexpress.com/item/1005005973866782.html)
* [1x DC/DC BUCK 3A MP1584 adjustable buck module regulator LM2596S](https://www.aliexpress.com/item/32841466894.html)
* [1x BMP180 Digital Barometric Pressure Sensor](https://www.aliexpress.com/item/32709141948.html)
* [2x RJ45 PCB connector](https://vikiwat.com/product/19790/konektor-rj45-f-pcb.html)
* [5x4, 1x6, Female pin headers ]
* [2x10 Male pin headers]
* [Plastic DIN mounted box-P912036](https://eshop-bg.com/produkt/%d0%bf%d0%bb%d0%b0%d1%81%d1%82%d0%bc%d0%b0%d1%81%d0%be%d0%b2%d0%b0-%d0%ba%d1%83%d1%82%d0%b8%d1%8f-%d0%b7%d0%b0-din-%d1%88%d0%b8%d0%bd%d0%b0-85x58x157%d0%bc%d0%bc/)
* [2x Panasonic PIR sensor](https://www.farnell.com/datasheets/2267095.pdf)
