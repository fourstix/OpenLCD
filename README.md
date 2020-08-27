OpenLCD 
=========

<table class="table table-hover table-striped table-bordered">
  <tr align="center">
   <td><a href="https://www.sparkfun.com/products/14072"><img src="https://cdn.sparkfun.com/assets/parts/1/1/9/2/5/14072-SparkFun_16x2_SerLCD_-_Black_on_RGB_3.3V-01.jpg"></a></td>
   <td><a href="https://www.sparkfun.com/products/14073"><img src="https://cdn.sparkfun.com/assets/parts/1/1/9/2/6/14073-SparkFun_16x2_SerLCD_-_RGB_on_Black_3.3V-01.jpg"></a></td>
   <td><a href="https://www.sparkfun.com/products/14074"><img src="https://cdn.sparkfun.com/assets/parts/1/1/9/2/7/14074-SparkFun_20x4_SerLCD_-_Black_on_RGB_3.3V-01.jpg"></a></td>
  </tr>
  <tr align="center">
    <td><a href="https://www.sparkfun.com/products/14072">SparkFun 16x2 SerLCD - Black on RGB 3.3V (LCD-14072)</a></td>
    <td><a href="https://www.sparkfun.com/products/14073">SparkFun 16x2 SerLCD - RGB on Black 3.3V (LCD-14073)</a></td>
    <td><a href="https://www.sparkfun.com/products/14074">SparkFun 20x4 SerLCD - Black on RGB 3.3V (LCD-14074)</a></td>
  </tr>
</table>

These AVR-based Serial Enabled LCDs are based on the HD44780 controller, and include an AVR ATmega328P with an Arduino compatible bootloader. They accept control commands via Serial, I2C and SPI. 

This repo contains the firmware that runs on the SerLCD hardware. If you are looking for the Arduino Library to talk to these devices please go [here](https://github.com/sparkfun/SparkFun_SerLCD_Arduino_Library).

And thank you to all those that helped make OpenLCD better:

* **fourstix** - [Creating](https://github.com/sparkfun/OpenLCD/pull/13) an Arduino library to drive OpenLCD directly, added pipe character escaping
* **makinako** - [Changing](https://github.com/sparkfun/OpenLCD/pull/18) EEPROM writes to updates to reduce NVM wear and tear
* **ALittleSlow** - [Fixed](https://github.com/sparkfun/OpenLCD/pull/21) logic bug on ignoreRX

Repository Contents
-------------------
* **/Firmware**
  * **/Examples**
  * **/OpenLCD**

Documentation
--------------
* **[SparkFun SerLCD Arduino Library](https://github.com/sparkfun/SparkFun_SerLCD_Arduino_Library)** - Makes printing to and controlling the SerLCD a snap!
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/avr-based-serial-enabled-lcds-hookup-guide)** - Basic hookup guide for the SparkFun Open LCD Products.
* **[SparkFun Fritzing repo](https://github.com/sparkfun/Fritzing_Parts)** - Fritzing diagrams for SparkFun products.
* **[SparkFun 3D Model repo](https://github.com/sparkfun/3D_Models)** - 3D models of SparkFun products. 
* **[SparkFun Graphical Datasheets](https://github.com/sparkfun/Graphical_Datasheets)** -Graphical Datasheets for various SparkFun products.

Product Versions
----------------
* OpenLCD
  * [LCD-14072](https://www.sparkfun.com/products/14072) - SparkFun 16x2 SerLCD - Black on RGB 3.3V
  * [LCD-14073](https://www.sparkfun.com/products/14073) - SparkFun 16x2 SerLCD - RGB on Black 3.3V
  * [LCD-14074](https://www.sparkfun.com/products/14074) - SparkFun 20x4 SerLCD - Black on RGB 3.3V

License Information
-------------------
The code is beerware; if you see me (or any other SparkFun employee) at the local, and you've found our code helpful, please buy us a round!

Distributed as-is; no warranty is given.
