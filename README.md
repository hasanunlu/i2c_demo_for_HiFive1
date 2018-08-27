# i2c_demo_for_HiFive1
Download freedom-e-sdk from https://github.com/sifive/freedom-e-sdk
Copy i2c_demo folder under freedom-e-sdk/software

for compiliation:
```
make software PROGRAM=i2c_demo BOARD=freedom-e300-hifive1
```
for uploading the binary:
```
make upload PROGRAM=i2c_demo BOARD=freedom-e300-hifive1
```
Sample console out:
```
core freq at 271758131 Hz
BIT-BANG I2C DEMO with MPU-6050 IMU
Power Management 1: 0x00
Power Management 1: 0x40
CHIP_ID: 0x68
DONE
Gravity in Z 0.0
Gravity in Z 0.93
Gravity in Z 0.92
Gravity in Z 0.93
Gravity in Z 0.92
Gravity in Z 0.93
Gravity in Z 0.93
Gravity in Z 0.93
Gravity in Z 0.94
Gravity in Z 0.93
```
