[![ SI7005](SI7005_I2C.png)](https://store.ncd.io/product/si7005-humidity-and-temperature-sensor-%C2%B14-5rh-%C2%B10-5c-i2c-mini-module/).

#  SI7005

The SI7005 is a digital relative humidity and temperature sensor.
This Device is available from www.ncd.io 

[SKU:SI7005]

(https://store.ncd.io/product/si7005-humidity-and-temperature-sensor-%C2%B14-5rh-%C2%B10-5c-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface SI7005 humidity and temperature sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/si7005-humidity-and-temperature-sensor-%C2%B14-5rh-%C2%B10-5c-i2c-mini-module/">SI7005 humidity and temperature sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python SI7005.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
