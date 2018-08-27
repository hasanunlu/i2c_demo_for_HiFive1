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
